# frozen_string_literal: true
source 'https://rubygems.org'

gemspec
gem 'rake'

group :development, :test do
  gem 'cucumber'
  gem 'faker', '~> 1.0'      # fix for breaking change in faker 2.x
  gem 'pry-nav', require: true
  gem 'pry-rescue', require: true
  gem 'rexml'
  gem 'rspec'
  gem 'rubocop', '~> 0.50.0'
  gem 'simplecov', '~> 0.13' # fix for breaking change in simplecov
  gem 'webmock'
end

group :development do
  gem 'guard-bundler', platforms: :mri
  gem 'guard-rspec', platforms: :mri

  gem 'rb-fchange', require: false # Windows
  gem 'rb-fsevent', require: false # OS X
  gem 'rb-inotify', require: false # Linux
  gem 'terminal-notifier-guard'

  gem 'ruby-prof', platforms: :mri
end

group :release do
  gem 'colorize'
  gem 'git'
  gem 'redcarpet', platforms: :mri
  gem 'yard'
end
