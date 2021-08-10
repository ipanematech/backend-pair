source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.2"

gem "rails",      "6.1.4"

gem "pg",         "1.2.3"
gem "puma",       "5.4.0"
gem "sass-rails", "6.0.0"
gem "webpacker",  "5.4.0"
gem "turbolinks", "5.2.1"
gem "jbuilder",   "2.11.2"
gem "bootsnap",   "1.6.0", require: false

gem "zip-codes", "0.2.1"


group :development, :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw]
  gem "rubocop", require: false
  gem "rubocop-performance"
  gem "rubocop-rails"
  gem 'rspec-rails', '~> 5.0', '>= 5.0.1'
end

group :development do
  gem "listen",                "3.4.1"
  gem "web-console",           "4.1.0"
  gem "spring"
  gem "spring-watcher-listen", "2.0.1"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "minitest-reporters"
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
