source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.2'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'font-awesome-rails'
gem 'jquery-rails'
gem 'sqlite3', :group => [:development, :test]
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'simple_form'
gem 'devise'
gem 'dotenv-rails'
gem 'omniauth-twitter'
gem 'omniauth-facebook', '~> 4.0'
gem 'pry-rails'
gem 'twitter'
gem 'koala'
gem 'delayed_job_active_record'
gem 'delayed-web', github: 'thebestday/delayed-web'
gem 'omniauth-linkedin-oauth2'
gem 'linkedin-oauth2', github: 'emorikawa/linkedin-oauth2', ref: 'ceb63460b8b45b7e00766ae3a4c3e361d76c6ffc'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
