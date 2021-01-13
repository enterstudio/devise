source "https://rubygems.org"

gemspec

gem "rails", "~> 5.1"
gem "omniauth", "~> 2.0", ">= 2.0.0"
gem "oauth2"
gem "omniauth-oauth2", ">= 1.7.1"
gem "rdoc"

gem "activemodel-serializers-xml", github: "rails/activemodel-serializers-xml"

gem "rails-controller-testing"

gem "responders", "~> 2.1"

group :test do
  gem "omniauth-facebook", ">= 4.0.0"
  gem "omniauth-openid"
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
