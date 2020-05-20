source 'http://rubygems.org'

gem 'rails', '5.2.4.3'
gem 'nokogiri'
gem 'mongoid', '6.0.0'
gem 'haml'
gem 'will_paginate', '>=3'
gem 'htmlentities', "~> 4.3.0"
gem 'devise', '~> 1.4.0'
gem 'lighthouse-api', '>= 2.0'
gem 'oruen_redmine_client', '>= 0.0.1', :require => 'redmine_client'
gem 'mongoid_rails_migrations', '>= 0.0.14'
gem 'useragent', '~> 0.3.1'
gem 'pivotal-tracker'
gem 'ruby-fogbugz', :require => 'fogbugz'
gem 'octokit'
gem 'inherited_resources'
gem 'SystemTimer', :platform => :ruby_18
gem 'hoptoad_notifier', '~> 2.4', '>= 2.4.11'
gem 'actionmailer_inline_css', '~> 1.3.1'

platform :ruby do
  gem 'bson_ext', '~> 1.4.0'
end

gem 'ri_cal'

group :development, :test do
  gem 'rspec-rails', '~> 2.8', '>= 2.8.0'
  gem 'webmock', :require => false
  gem 'factory_girl', '~> 1.3.3'
  gem 'factory_girl_rails', '~> 1.0.1'
  unless ENV['TRAVIS']
    gem 'ruby-debug', :platform => :mri_18
    gem 'ruby-debug19', :platform => :mri_19, :require => 'ruby-debug'
  end
end

group :test do
  gem 'rspec', '~> 2.6'
  gem 'database_cleaner', '~> 0.6.0'
  gem 'email_spec', '>= 1.2.1'
end

group :heroku do
  gem 'thin'
end

