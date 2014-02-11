source 'https://rubygems.org'
ruby '2.1.0'
#ruby-gemset=rails_4_0_2

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'

  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'growl'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
end

group :development do
  gem 'guard-livereload', require: false
  gem 'rack-livereload'

  # Use capistrano for deployment
  gem 'capistrano'
  gem 'capistrano-rvm'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
end

group :test do
  gem 'capybara', '2.2.1'
end

# Use device for account management
gem 'devise'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use bootstrap-sass for views
gem 'bootstrap-sass', '~> 3.1.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Use jquery-turbolinks to fix onready event issue
gem 'jquery-turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# Use bower-rails to load external packages with bower
gem "bower-rails"

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]