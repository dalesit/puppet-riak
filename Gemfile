#ruby=2.1.5
#ruby-gemset=puppet-riak
source "https://rubygems.org"

group :test do
  gem "rake"
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 4.0.0'
  gem "rspec-puppet", :git => 'https://github.com/rodjek/rspec-puppet.git'
  gem "puppetlabs_spec_helper"
  gem "metadata-json-lint"
  gem "rspec-puppet-facts"
end

group :development do
  gem "travis"
  gem "travis-lint"
  gem "vagrant-wrapper"
  gem "puppet-blacksmith"
  gem "guard-rake"
  gem "json"
end

group :system_tests do
  gem "beaker"
  gem "beaker-rspec"
end
