source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby ">= 3.3.6"

group :development, :test do
  gem "toml-rb"
  gem "heroku_hatchet"
  gem "rspec-core"
  gem "rspec-expectations"
  gem "excon"
  gem "rake"
  gem "parallel_tests"
  gem 'rspec-retry'
  gem 'json'
  gem 'ci-queue', github: "schneems/ci-queue", branch: "schneems/allow-hosted-redis"
  gem 'redis'
  gem 'dead_end'
end
