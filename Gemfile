source "https://rubygems.org"

if !!File::ALT_SEPARATOR
  gemspec :name => 'rest-client.windows'
else
  gemspec :name => 'rest-client'
end

group :test do
  gem 'rake'
end

gem 'rake'
gem 'rspec'

gem 'coveralls', require: false
