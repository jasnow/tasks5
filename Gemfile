source 'https://rubygems.org'

gem 'rails', '5.0.0.beta3'

gem 'sqlite3'
gem 'sass'
gem 'coffee-script'
gem 'uglifier'
gem 'jquery-rails'
gem 'overcommit'

group :development do
  gem 'dawnscanner', require: false
end

group :test, :development do
  gem 'rspec-rails', '3.5.0.beta2'
  gem 'capybara'

  gem 'rb-inotify' if /linux/ =~ RUBY_PLATFORM
  gem 'launchy'
end
