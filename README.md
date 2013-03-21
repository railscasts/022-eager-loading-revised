# RailsCasts Episode #22: Eager Loading (revised)

http://railscasts.com/episodes/22-eager-loading-revised

Requires Ruby 1.9.2 or higher.


### Commands used in rails console

```
Product.joins(:category, :reviews)
Product.joins(:category, :reviews => :user)
Product.joins("left outer join categories on category_id = categories.id")
```
