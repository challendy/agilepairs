source 'http://rubygems.org'
source 'http://gemcutter.org'
# Bundle edge Rails instead:

gem "rails", "3.0.0"
gem "mongoid", :git => "git://github.com/mongoid/mongoid.git"
gem "bson_ext", "1.0.4"
gem "haml", ">=3.0.13", :git => "git://github.com/nex3/haml.git"
gem "devise", ">=1.1.2"

# Fast Date Time Parsing for Ruby...
#http://www.rubyinside.com/home_run-rubys-date-and-datetime-classes-but-20-200x-faster-3707.html
gem "home_run", :git => 'git://github.com/jeremyevans/home_run.git'

group :development do
  gem "hpricot"
  gem "ruby_parser"
  gem "haml-rails",  :git => 'git://github.com/indirect/haml-rails.git'
  gem "rails3-generators", :git => "git://github.com/indirect/rails3-generators.git"
end

#Do this to have rake spec generate
group :development, :test do
  gem 'rspec-rails', '>= 2.0.0.beta.10'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'cucumber-rails'
  gem 'cucumber', '>=0.7.3'
  gem 'spork'
  gem 'launchy'
  gem "factory_girl", '>=1.3.2'
  gem 'factory_girl_rails'
  gem 'jspec'
  gem 'remarkable_mongoid'
end

# Use unicorn as the web server
 gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
