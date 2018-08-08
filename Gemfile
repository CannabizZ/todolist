source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1'
gem 'jquery-rails'
gem 'twitter-bootstrap-rails'
gem 'simple_form'

group :assets do
    gem 'sass-rails', '~> 5.0'
    gem 'uglifier', '>= 1.3.0'
    gem 'coffee-rails', '~> 4.2'
    gem 'therubyracer', platform: :ruby
end

group :production do
  gem 'pg'
end

group :development, :test do
    gem 'byebug'
end

group :development do
    gem 'web-console', '~> 2.0'
    gem 'sqlite3'
end




