source 'http://rubygems.org'
# Add dependencies required to use your gem here.
# Example:
#   gem 'activesupport', '>= 2.3.5'

gem 'sinatra', '~> 1.2.1', :require => 'sinatra/base'
gem 'dragonfly', '~> 0.9.1'
gem 'addressable', '~> 2.2', :require => 'addressable/uri'

gem 'haml', '~> 3.0'
gem 'typhoeus', '~> 0.2.4'
gem 'activesupport', '>= 2.0.0', :require => false

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development do
  gem 'jeweler', '~> 1.5'
  gem 'rcov', '>= 0'
end

group :development, :test do
  # rake 0.9.0 breaks w/ ActiveSupport
  gem 'rake', '~> 0.8.7'
  
  gem 'rack-test'
  gem 'rspec', '~> 2.4'
  gem 'webmock', '~> 1.6'
  gem 'imagesize', '~> 0.1'
end

group :production do
  gem 'newrelic_rpm', :require => false
end
