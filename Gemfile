# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.1'
gem 'activeadmin'
gem 'bootsnap', require: false
gem 'bundle-audit'
gem 'devise'
gem 'devise_token_auth'
gem 'jbuilder', '~> 2.5'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.2'
gem 'sdoc'

group :test do
  gem 'faker', git: 'https://github.com/stympy/faker.git', branch: 'master'
  gem 'rails-controller-testing'
  gem 'shoulda-matchers', '4.0.0.rc1'
end

group :development, :test do
  gem 'bullet'
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 3.8'
  gem 'rspec_junit_formatter'
  gem 'rubocop-rspec'
end

group :development do
  gem 'annotate'
  gem 'rubocop', '~> 0.63.0', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
