# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4', '>= 6.1.4.1'

gem 'bootsnap', '>= 1.4.4', require: false # https://rubygems.org/gems/bootsnap
gem 'dotenv-rails', '~> 2.7', '>= 2.7.6' # https://rubygems.org/gems/dotenv-rails
gem 'jsonapi-serializer', '~> 2.2' # https://rubygems.org/gems/jsonapi-serializer
gem 'pg', '~> 1.1' # https://rubygems.org/gems/pg
gem 'puma', '~> 5.0' # https://rubygems.org/gems/puma

# gem 'rack-cors' # https://rubygems.org/gems/rack-cors

group :development, :test do
  gem 'factory_bot_rails', '~> 5.1', '>= 5.1.1' # https://rubygems.org/gems/factory_bot_rails
  gem 'pry-byebug', '~> 3.9', platform: :mri # https://rubygems.org/gems/pry-byebug
  gem 'pry-rails', '~> 0.3.9' # https://rubygems.org/gems/pry-rails
  gem 'rspec-rails', '~> 4.1' # https://rubygems.org/gems/rspec-rails
end

group :development do
  gem 'annotate', '~> 3.0', '>= 3.0.3' # https://rubygems.org/gems/annotate
  gem 'brakeman', '~> 5.1', '>= 5.1.2' # https://rubygems.org/gems/brakeman
  gem 'listen', '~> 3.3' # https://rubygems.org/gems/listen
  gem 'rails_best_practices', '~> 1.20' # https://rubygems.org/gems/rails_best_practices
  gem 'rubocop', require: false # https://rubygems.org/gems/rubocop
  gem 'rubocop-performance', require: false # https://rubygems.org/gems/rubocop-performance
  gem 'rubocop-rails', require: false # https://rubygems.org/gems/rubocop-rails
  gem 'rubocop-rspec', require: false # https://rubygems.org/gems/rubocop-rspec
  gem 'spring', '~> 2.1' # https://rubygems.org/gems/spring
  gem 'spring-watcher-listen', '~> 2.0.1' # https://rubygems.org/gems/spring-watcher-listen
end

group :test do
  gem 'faker', '~> 2.13' # https://rubygems.org/gems/faker
  gem 'shoulda-matchers', '~> 4.1', '>= 4.1.2' # https://rubygems.org/gems/shoulda-matchers
  gem 'simplecov', '~> 0.13.0', require: false # https://rubygems.org/gems/simplecov
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
