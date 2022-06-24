# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rspec'

ruby '3.1.2'
gem 'bootsnap', require: false
gem 'bootstrap', '~> 5.1', '>= 5.1.3'
gem 'importmap-rails'
gem 'jbuilder'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.3'
gem 'rbenv', '~> 9001'
gem 'rubocop', '~> 1.30', '>= 1.30.1'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'sqlite3', '~> 1.4'
  gem 'web-console'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
