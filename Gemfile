# Edit this Gemfile to bundle your application's dependencies.
# This preamble is the current preamble for Rails 3 apps; edit as needed.
source 'http://rubygems.org'

gem 'rails', '3.0.1'

if RUBY_PLATFORM !~ /mswin|mingw/
  gem 'rdiscount', '1.6.5'

  gem "ruby-stemmer", "~> 0.8.2", :require => "lingua/stemmer"
  gem "sanitize", "1.2.1"

  gem 'magic'
  gem 'nokogiri'
  gem 'mechanize'
else
  gem "maruku", "0.6.0"
end

# ui
gem "haml"
gem 'compass', '0.10.6.pre.1'
gem "compass-colors", "0.3.1"
gem "fancy-buttons", "0.5.5"

# mongodb
gem 'bson', '1.1.1'
gem 'plucky', '0.3.6'

gem 'mongo', '1.1.1'
gem 'jnunemaker-validatable', '1.8.4'
gem 'mongo_mapper', '0.8.6'
gem 'mongomapper_ext', '0.5.1'

# utils

gem "geoip"
gem "whatlanguage", "1.0.0"
gem "uuidtools", "2.1.1"
gem "magent", "0.4.2"

gem 'goalie'
gem 'dynamic_form'

gem "differ", "0.1.1"
gem "rack-recaptcha", "0.2.2", :require => "rack/recaptcha"

gem "twitter-text", "1.1.8"
gem 'sanitize', '1.2.1'


# authentication
gem 'omniauth', '~> 0.1.6'
gem 'multiauth', :path => "vendor/gems/multiauth/"

gem 'orm_adapter'
gem 'devise', :git => 'http://github.com/plataformatec/devise.git', :branch => 'omniauth'


group :development do
  gem 'hpricot'
  gem 'ruby_parser'
  gem 'mongrel', '1.2.0.pre2'
  gem 'niftier-generators', '0.1.2'
end
