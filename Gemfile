source "https://rubygems.org"

ruby file: '.ruby-version'

# Base app
gem "puma",    ">= 5.0"
gem "rails",   "~> 7.1.3", ">= 7.1.3.2"
# gem "redis",   ">= 4.0.1"
gem "sqlite3", "~> 1.7", force_ruby_platform: true

# gem "bcrypt", "~> 3.1.7"

gem "bootsnap", require: false

gem "sprockets-rails"
gem "importmap-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "slim"

# CSS
gem "bulma-rails", "~> 1.0.0"
gem "dartsass-rails"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem 'faker'
  gem 'rspec-rails', '~> 6.1.0'
  gem 'factory_bot_rails'
end

group :development do
  gem "web-console"
  gem 'solargraph'
end

group :test do
  gem 'shoulda-matchers', '~> 6.0'
  gem 'database_cleaner-active_record'
end
