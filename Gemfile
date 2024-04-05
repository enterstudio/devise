source "https://rubygems.org"

gemspec

gem "rails", "~> 7.0", ">= 7.0.8.1"
gem "omniauth", "~> 1.7", ">= 1.7.0"
gem "oauth2", ">= 1.4.0"
gem "omniauth-oauth2", ">= 1.5.0"
gem "rdoc", ">= 6.3.4.1"

gem "activemodel-serializers-xml", github: "rails/activemodel-serializers-xml"

gem "rails-controller-testing", ">= 1.0.3"

gem "responders", "~> 3.0", ">= 3.0.0"

group :test do
  gem "omniauth-facebook", ">= 5.0.0"
  gem "omniauth-openid", ">= 2.0.1"
  gem "webrat", "0.7.3", require: false
  gem "mocha", "~> 1.1", require: false
end

platforms :jruby do
  gem "activerecord-jdbc-adapter"
  gem "activerecord-jdbcsqlite3-adapter"
  gem "jruby-openssl"
end

platforms :ruby do
  gem "sqlite3"
end

# TODO:
# group :mongoid do
#   gem "mongoid", "~> 4.0.0"
# end
