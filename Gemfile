# frozen_string_literal: true

source "https://rubygems.org"
ruby "2.7.3"

gem "rails", "~> 6.1", ">= 6.1.7.5"

gem "asciidoctor", "~> 2.0.0"
gem "elasticsearch", "2.0.2"
gem "iso8601"
gem "octokit"
gem "puma"

gem "diffy"
gem "nokogiri"

# Assets
gem "sass-rails"
gem "uglifier"

group :development do
  gem "awesome_print"
  gem "better_errors"
  gem "binding_of_caller"
  gem "foreman"
end

group :development, :test do
  gem "dotenv-rails", ">= 2.8.0"
  gem "listen"
  gem "pry-byebug"
  gem "rubocop-github", ">= 0.17.0"
  gem "ruby-prof"
  gem "sqlite3"
end

group :test do
  gem "database_cleaner", ">= 2.0.2"
  gem "fabrication"
  gem "factory_bot_rails"
  gem "rails-controller-testing"
  gem "rspec-rails", ">= 5.0.3"
  gem "shoulda"
  gem "vcr"
  gem "webmock"
end

group :production do
  gem "pg"
  gem "rack-timeout"
  gem "rails_12factor"
  gem "redis-rails"
end
