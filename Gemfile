source 'https://rubygems.org'
gemspec

group :development do
  gem 'rb-fsevent', :require => RUBY_PLATFORM.include?('darwin') && 'rb-fsevent'
  gem 'growl', :require => RUBY_PLATFORM.include?('darwin') && 'growl'
  gem 'guard'
  gem 'guard-bundler'
  gem 'guard-rspec'
end

gem 'simplecov', :group => :test, :platforms => :mri_19, :require => false
