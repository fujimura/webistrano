source 'http://rubygems.org'

gem 'rails', '3.2.5'

gem 'jquery-rails'
gem 'prototype-rails'
gem 'exception_notification'

gem 'capistrano'#, '2.5.19'
gem 'open4',      '0.9.3'
gem 'syntax',     '1.0.0'
gem 'version_fu', :github => 'jmckible/version_fu'
gem 'devise'
gem 'devise-encryptable'
gem 'haml'

group :development do
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

group :test do
  gem 'sqlite3-ruby', :require => 'sqlite3'
  gem 'test-unit', '2.0.9', :require => 'test/unit'
  gem 'mocha'
  gem 'factory_girl_rails'
end

group :production do
  gem 'mysql2'
  gem 'unicorn'
end

group :assets do
  gem 'compass'
  gem 'compass-rails'
  gem 'sass-rails'
end
