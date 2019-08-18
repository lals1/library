source 'https://rubygems.org'
ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Language list for books, see https://github.com/scsmith/language_list
gem 'language_list'
gem 'bootsnap', require: false
gem 'listen'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'bcrypt'
gem "font-awesome-rails"
gem "paperclip"
#gem 'aws-sdk', '~> 2.3'
gem 'aws-sdk-s3'
gem 'teacup-rails'
gem 'will_paginate'
gem 'isbn_validation'
gem 'email_validator'
#gem 'puma'


group :production do
  gem 'pg', '~> 0.18'
  gem 'rails_12factor'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'pry-rails'
  gem 'rails_real_favicon'
end

group :development, :test do
  gem 'capybara'
  gem "factory_bot_rails"
  gem 'rspec-rails', '~> 3.5'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'better_errors'
  gem 'sqlite3', '~> 1.3', '< 1.4'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'rails_layout'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
