source 'https://rubygems.org'

gem 'rails', '5.1.1'
gem 'govuk_app_config', '~> 0.2.0'
gem 'plek', '1.12.0'

gem 'mongoid', '~> 6.2'
gem "mongoid_rails_migrations", git: "https://github.com/alphagov/mongoid_rails_migrations", branch: "avoid-calling-bundler-require-in-library-code-v1.1.0-plus-mongoid-v5-fix"

gem 'logstasher', '0.6.2'
gem 'unicorn', '~> 4.9.0'

group :development, :test do
  gem 'rack-handlers', '~> 0.7', require: 'rack/handler/rails-server'
  gem 'rspec-rails', '~> 3.5'
  gem 'database_cleaner', '1.6.1'
  gem 'factory_girl_rails', '4.2.1'
  gem 'ci_reporter_rspec', '~> 1.0.0'
  gem 'webmock', '~> 1.20.4', require: false
  gem 'govuk-lint'
  gem 'byebug'
end
