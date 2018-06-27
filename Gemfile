source 'https://rubygems.org'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0'

gem 'sass-rails', '~> 4.0.5'
gem 'uglifier',                     '>= 1.3.0'
gem 'coffee-rails',                 '~> 4.0.0'
gem 'jquery-rails'
gem 'figaro', '~> 0.7.0'
gem 'devise',                       '~> 3.2.2'
gem 'omniauth',                     '~> 1.2.1'
gem 'omniauth-facebook',            '~> 1.6.0'
gem 'omniauth-google-oauth2',       '~> 0.2.2'
# gem 'paper_trail',
# gem 'carrierwave',
# gem 'rmagick',
# gem 'fog',
# gem 'geocoder',
# gem 'ember-rails',                  '~> 0.14.1'
gem 'font-awesome-rails',           '~> 4.0.3'
gem 'nokogiri',                     '~> 1.6.1'
gem 'mechanize' #,                   '~> 2.7.3'
gem 'brakeman'
gem 'minitest',                     '~> 5.3.3'
gem 'minitest-rails',               '~> 2.0.0.beta1'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',             group: :doc


# Use one as the app server
# gem 'unicorn'
# gem 'passenger'


group :production do
  gem 'rails_12factor'
  gem 'pg',                         '~> 0.17.1'
end


# Use Capistrano for deployment
group :development do
  gem 'spring'
  gem 'capistrano-rails'
end


group :test do
  gem 'minitest-rails-capybara',    '~> 2.0.0.beta1'
  gem 'launchy',                    '~> 2.4.2'
  # gem 'turn',                       '~> 0.9.7'
  # gem 'minitest-focus',             '~> 1.1.0'
  gem 'simplecov',                  :require => false
end

group :development, :test do
  gem 'sqlite3' #to be added to below env when pg is added
# gem 'debugger'
  gem 'capybara-webkit',            '~> 1.1.1'
  gem 'pry-rails',                  '~> 0.3.2'
  gem 'faker',                      '~> 1.2.0'
  gem 'database_cleaner',           '~> 1.2.0'
  gem 'selenium-webdriver',         '~> 2.39.0'
  gem 'qunit-rails',                '~> 0.0.7'
  # gem 'factory_girl_rails'
end
