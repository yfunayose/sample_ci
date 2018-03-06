source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.5'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.3.18', '< 0.5'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Device
gem 'devise'
gem 'omniauth'
# Facebook
gem 'omniauth-facebook'
gem 'koala'
gem 'faraday', '<= 0.9', '>= 0.8'

# instagram
gem 'instagram', :git => 'git://github.com/Instagram/instagram-ruby-gem.git'

# session管理
gem 'activerecord-session_store'

# 足跡保存
gem 'redis', '~>3.2'
gem 'redis-objects'
gem 'redis-rails'

# Admin
gem 'activeadmin'
gem 'cancancan'

# pager
gem 'kaminari'

# bootstrap(bootswatch)
gem 'twitter-bootswatch-rails', '~> 3.1.1'
gem 'twitter-bootswatch-rails-helpers'
gem 'execjs'
gem 'less-rails', git: 'https://github.com/MustafaZain/less-rails'

# newrelic
gem 'newrelic_rpm'

# 定数管理
gem 'config'

# image
gem 'carrierwave', '~> 0.11'
gem 'carrierwave-processing'
gem 'rmagick'
# For Carrierwave
gem 'fog'
gem "tinify"

# AWS
gem 'aws-sdk'

# cron管理
gem 'whenever', require: false

# slack
gem 'slack-api'

# メンテナンスモード
gem 'turnout'

# 検索
gem 'ransack'

gem 'browser', '~> 2.1'

# GrowthPush
gem 'growthpush'

# JavaScript libraries.
gem 'lodash-rails'
gem 'slick_rails'

# CSS libraries
gem 'font-awesome-rails'

# React integration
# gem "react_on_rails", "~> 9.0.3"
# gem "webpacker", "~> 3.0"

gem 'bootstrap-sass', '~> 3.3.6'

# Markdown parser
gem 'redcarpet'

gem 'roadie-rails', '~> 1.0'

gem "bugsnag"

gem 'sidekiq'
gem 'redis-namespace'

gem 'openid_connect', '~> 1.1'

# Google reCAPTCHA
gem "recaptcha", require: "recaptcha/rails"

gem 'foreman'

gem 'dalli'
gem 'jwt'
gem 'firebase'
gem 'lograge'
gem 'rack-cors'

group :staging, :development, :test do
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'pry-doc'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'rubocop', '~> 0.53.0'
  gem "rails_best_practices"
  gem 'brakeman'
  gem 'guard-brakeman'
  gem 'capistrano'
  gem 'capistrano-rails', '1.1.3'
  gem 'capistrano-yarn'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano3-puma'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
