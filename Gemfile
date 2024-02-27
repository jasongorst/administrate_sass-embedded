source 'https://rubygems.org'
ruby "3.2.2" unless ENV["CI"]

gemspec

gem "administrate-field-image"
gem "faker"
gem "front_matter_parser"
gem "globalid"
gem "kaminari-i18n"
gem "pg"
gem "pundit"
gem "redcarpet"
gem "sentry-raven"
gem "unicorn"

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "i18n-tasks", "1.0.13"
  gem "pry"
  gem "yard"
end

group :test do
  gem "ammeter"
  gem "capybara"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "selenium-webdriver", "= 4.9.0"
  gem "shoulda-matchers"
  gem "timecop"
  gem "webdrivers"
  gem "webmock"
  gem "webrick"
  gem "xpath", "3.2.0"
end

group :staging, :production do
  gem "rack-timeout"
  gem "uglifier"
end
