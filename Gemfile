source 'https://rubygems.org'
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

group :assets do
  # Use SCSS for stylesheets
  gem 'sass-rails'
  # CSS Authoring Framework
  gem 'compass-rails'
  # Twitter's toolkit for kickstarting CSS
  gem 'bootstrap-sass'
end



# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
# gem 'coffee-rails', '~> 4.0.0'
gem 'iced-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Use Simple Form for forms
gem 'simple_form'

# Use Slim template engine for templates
gem 'slim-rails'

# Turbolinks makes following links in your web application faster.
# Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  # gem 'sdoc', require: false
  gem 'yard-rails'
end

# Unit tests
group :test do
  gem 'rspec-rails'
  gem 'factory_girl'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
gem 'byebug', group: [:development, :test]

# Local gems
gemfile_local = File.join(File.dirname(__FILE__), 'Gemfile.local')
if File.readable?(gemfile_local)
  puts "Loading #{gemfile_local}..." if $DEBUG
  instance_eval(File.read(gemfile_local))
end
