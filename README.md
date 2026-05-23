# Welcome! 👋

```ruby
class matthewscott364
  attr_accessor :name, :pronouns, :current_role, :passions

  def initialize(
    name: "Matthew Scott",
    location: "North Brunswick, NJ, United States"
    current_role: "College Student, Analytics Engineer",
    passions: ["analytics-engineering", "data-engineering", "machine learning"]
  )
    @name = name
    @pronouns = pronouns
    @current_role = current_role
    @passions = passions
  end

  def say_hi
    "Hi! Thanks for dropping by. :-)"
  end
end

me = matthewscott364.new
puts me.say_hi

```
