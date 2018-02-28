source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# core

gem 'rails', '~> 5.1.1'
gem 'puma', '~> 3.7'
gem 'figaro'
gem 'paranoia'


# db

gem 'bcrypt'
gem 'pg', '~> 0.18'
gem "pgcli-rails"


# cache

gem 'dalli'
gem 'kgio'
gem 'rack-cache'


# frontend

gem 'haml'
gem 'haml-rails'
gem 'simple_form'
gem 'momentjs-rails'
gem 'sass-rails'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'kaminari'

gem 'uglifier'
gem 'yui-compressor'
gem 'jbuilder'

gem 'rails-assets-tether'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'


# auth

gem 'cancancan'
gem 'devise'
gem 'devise-i18n'


# utilities

gem "marco-polo"


group :development, :test do
  gem 'byebug'
  gem 'factory_bot_rails'
  gem 'pry'
  gem 'pry-rails'
  gem 'timecop'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'

  # Preview mail in the browser instead of sending.
  gem 'letter_opener'

  gem 'metric_fu'
  gem 'rails_best_practices'

  gem 'listen'
end

group :test do
  gem 'database_cleaner'
  gem 'guard-rspec'
  gem 'rails-controller-testing'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'spring-commands-rspec'

  gem 'simplecov'
  gem 'simplecov-rcov'

  gem 'terminal-notifier-guard', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
