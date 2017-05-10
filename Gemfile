path = File.dirname(ENV['BUNDLE_GEMFILE'] || '.')
ruby File.read(File.join(path, '.circle-ruby')).chomp
source 'https://rubygems.org'

gem 'sinatra', '~> 1.4.6'
gem 'thin', '~> 1.7.0'
gem 'twilio-ruby', '~> 4.13.0'
gem 'githubstats', '~> 1.3.1'
gem 'basiccache', '~> 1.0.0'
gem 'redis', '~> 3.3.0'

group :development do
  gem 'rubocop', '~> 0.48.0'
  gem 'rake', '~> 12.0.0'
  gem 'codecov', '~> 0.1.1'
  gem 'rspec', '~> 3.6.0'
  gem 'fuubar', '~> 2.2.0'
end
