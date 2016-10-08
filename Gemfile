source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'

# ActiveModel::Serializers allows you to generate your JSON
# in an object-oriented and convention-driven manner.
gem 'active_model_serializers', '~> 0.10.2'
# A set of Rails responders to dry up your application
gem 'responders', '~> 2.3'

group :doc do
  gem 'yard'
  gem 'kramdown'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'spring'
  gem 'factory_girl_rails'
  gem 'ffaker'
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rspec-its'
  gem 'database_cleaner'
  gem 'guard-rails'
  gem 'guard-rspec'
  # Send notifications on OS-X
  gem 'terminal-notifier', require: false
  gem 'terminal-notifier-guard', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
