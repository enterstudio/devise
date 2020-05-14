source "https://rubygems.org"

gemspec

gem "rails", "~> 5.1", ">= 5.1.0"
gem "omniauth", "~> 1.6", ">= 1.6.1"
gem "oauth2", ">= 1.3.1"
gem "omniauth-oauth2", ">= 1.4.0"
gem "rdoc"

gem "activemodel-serializers-xml", github: "rails/activemodel-serializers-xml"

gem "rails-controller-testing", ">= 1.0.1"

gem "responders", "~> 2.4", ">= 2.4.0"

group :test do
  gem "omniauth-facebook", ">= 4.0.0"
  gem "omniauth-openid", ">= 1.0.1"
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
