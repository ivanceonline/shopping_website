# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.2.3"
gem "dotenv-rails"
gem "devise"
gem "toastr-rails"
# Use mysql as the database for Active Record
gem "mysql2"
gem "puma", "~> 4.3"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "bootstrap-sass", "~> 3.4.1"
gem "sassc-rails", ">= 2.1.0"
gem "jquery-rails"
gem "chartkick"
gem 'groupdate'
gem "coffee-rails", "~> 4.2"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "font-awesome-sass", "~> 5.8.1"
gem "faker"
gem 'sidekiq'
gem "kaminari"
gem "carrierwave"
gem "mini_magick"
gem "ransack"
gem "friendly_id", "~> 5.2.4"
gem "magnific-popup-rails", "~> 1.1.0"
gem "config"
gem "faker"
gem "bootstrap"
gem "stripe-rails"
gem "bootsnap", ">= 1.1.0", require: false
gem "ckeditor", github: 'galetahub/ckeditor'
gem "cancancan", "~> 2.0"
gem 'gmaps4rails'
group :development, :test do
  gem "pry-rails"
  gem "rspec-rails", "~> 3.8"
  gem "rubocop-rails", require: false
  gem "shoulda-matchers"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem "slim-rails"
