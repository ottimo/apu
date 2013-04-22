source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.beta1'

gem 'sqlite3'

group :development,:test do
  gem "rspec-rails"
  gem "rspec"
  gem "email_spec"
  gem "capybara"
  
  #  sudo apt-get install libqt4-dev libqtwebkit-dev
  #gem "capybara-webkit"

  # http://phantomjs.org/
  gem "poltergeist"

  gem 'jasmine'
  #gem 'jasminerice'
  gem 'guard-jasmine'

  gem "factory_girl_rails"
  gem "guard-rspec"
  gem "database_cleaner"
  gem "webrat"
  gem "cucumber"
  gem "guard-cucumber"
  gem 'rb-inotify', '~> 0.9', :require => false  
  gem 'shoulda-matchers'

  #per il sistema di template
end

group :test do
  gem "cucumber-rails"
end

group :development do
  gem 'awesome_print'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'pry-debugger'
  gem 'meta_request', '0.2.1' 
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'bootstrap-sass'  
  gem 'sass-rails',   '~> 4.0.0.beta1'
  gem 'coffee-rails', '~> 4.0.0.beta1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'aasm'

gem 'jquery-rails'
gem 'angularjs-rails'

gem "haml-rails"

gem "devise", :git => 'git://github.com/plataformatec/devise.git', :branch => 'rails4'
gem "cancan"

gem "thin"

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', group: :development
# Deploy with Capistrano
gem 'capistrano'
#gem 'rvm-capistrano'
gem 'rvm-capistrano', '1.3.0.rc1'

# To use debugger
# gem 'debugger'
