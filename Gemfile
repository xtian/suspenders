$:.push File.expand_path('../lib', __FILE__)
require 'suspenders/version'

source 'https://rubygems.org'

group :dist do
  gem 'bitters', '~> 0.10.0'
  gem 'bundler', '~> 1.3'
  gem 'rails', Suspenders::RAILS_VERSION
end

group :test do
  gem 'aruba', '~> 0.5'
  gem 'cucumber', '~> 1.2'
  gem 'rspec', '~> 2.0'
  gem 'capybara', '~> 2.2', '>= 2.2.0'
end
