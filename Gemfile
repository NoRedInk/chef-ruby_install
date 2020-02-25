source 'https://rubygems.org'

gem 'berkshelf', '~> 3.2'
gem 'chef', '~> 12.3', '>= 12.3.0'
gem 'rubocop'
gem 'foodcritic', '~> 3.0', '>= 3.0.3'
gem 'chefspec', '~> 4.2', '>= 4.2.0'
gem 'stove', '~> 3.2'
gem 'rake', '>= 12.3.3'

group :integration do
  gem 'test-kitchen', '~> 1.4'
  gem 'kitchen-vagrant'
  gem 'kitchen-ec2'
  gem 'unf' # Stop Fog (used by kitchen-ec2) complaining
  gem 'serverspec'
end
