##  Configure

`config/application.rb`

```ruby
module Bowerails
  class Application < Rails::Application

    # Configure Bower
    config.assets.paths << Rails.root.join('vendor', 'assets', 'bower_components')
  end
end
```
