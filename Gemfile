source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.2", ">= 7.0.2.3"

gem "sprockets-rails"

gem "pg", "~> 1.1"

gem "puma", "~> 5.0"

gem "importmap-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "jbuilder"

gem "redis", "~> 4.0"

# gem "kredis"

# gem "bcrypt", "~> 3.1.7"

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby]

gem "bootsnap", require: false


# gem "sassc-rails"

# gem "image_processing", "~> 1.2"

gem 'local_time'

gem 'devise'

gem 'devise_invitable'

gem 'rolify'

gem 'cancancan'

gem 'immutable-struct'

gem 'sidekiq'

gem 'sinatra', require:nil 

gem 'gravatar_image_tag'

gem 'slack-notifier'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem 'rspec-rails'
  gem 'rails-controller-testing'
  gem 'capybara'
  gem 'simplecov', :require => false, :group => :test
  gem "factory_bot_rails"
end

group :development do
  gem "web-console"
  gem "rack-mini-profiler"
  gem "spring"
  gem "letter_opener"
  gem 'foreman'
end

gem 'rack-cors', :require => 'rack/cors'



gem "tailwindcss-rails", "~> 2.3"
