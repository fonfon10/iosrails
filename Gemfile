source 'https://rubygems.org'

ruby '2.3.1'

gem 'delayed_job_active_record', '>= 4.0.0'
gem 'email_validator'
gem 'geocoder'
gem 'jbuilder'
gem 'oj'
gem 'pg'
gem 'rack-timeout'
gem 'rails'
gem 'recipient_interceptor'
gem 'unicorn'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'foreman'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails', '>= 2.14'
end

group :test do
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'webmock'
end

group :staging, :production do
  gem 'rails_12factor'
end
