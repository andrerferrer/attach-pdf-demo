This is a Demo for showcasing how to attach pdf to a model

1. Install active storage and migrate
```shell
rails active_storage:install
rails db:migrate
```
2. Add the relationship to your model
```ruby
class Article < ApplicationRecord
	# You can call this whatever you want
	# has_one_attached :banana
	has_one_attached :pdf
end
```