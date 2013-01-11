source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.11'
gem 'pg', :platforms => :ruby
gem 'activerecord-jdbcpostgresql-adapter', :platforms => :jruby
gem 'unicorn', :platforms => :ruby
gem 'newrelic_rpm', :platforms => :ruby

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development, :test do
  gem 'activerecord-jdbcsqlite3-adapter', :platforms => :jruby
  gem 'sqlite3', :platforms => :ruby
  gem 'rspec-rails', '~> 2.0'
end

group :development do
  gem 'foreman'
  gem 'nifty-generators'
  gem 'rails-erd'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-cucumber'
end

group :test do
  gem 'mocha', :require => false
  gem 'factory_girl_rails', '~> 4.0'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  gem 'capybara'
  gem 'simplecov', :require => false
  gem 'simplecov-rcov', :require => false
end

