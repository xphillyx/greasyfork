source 'https://rubygems.org'

ruby '2.6.6'

gem 'bootsnap'
gem 'daemons'
gem 'delayed_job', '>= 4.1.9'
gem 'delayed_job_active_record', '>= 4.1.5'
gem 'devise', '>= 4.7.2'
gem 'devise-i18n', git: 'https://github.com/tigrish/devise-i18n.git'
gem 'diffy'
gem 'mini_racer'
gem 'mysql2'
gem 'newrelic_rpm'
gem 'public_suffix'
gem 'rails', '~> 7.1.0'
gem 'rails-i18n', '>= 7.0.1'
gem 'redcarpet'
gem 'sanitize', '>= 6.0.0'
gem 'sass-rails' # Just for the compressor
gem 'sidekiq', '>= 6.0.7'
gem 'strip_attributes', '>= 1.12.0'
gem 'thinking-sphinx', '>= 5.0.0'
gem 'transifex-ruby', git: 'https://github.com/tmaesaka/transifex-ruby.git'
gem 'ts-delayed-delta'
gem 'uglifier'
gem 'will-paginate-i18n'
gem 'will_paginate'

gem 'hiredis'
gem 'redis'

gem 'ace-rails-ap'
gem 'detect_language'
gem 'email_address'
# https://github.com/iGEL/it/pull/27
gem 'it', git: 'https://github.com/JasonBarnabe/it', branch: 'raise-symbol'
gem 'memoist'
gem 'omniauth', '>= 2.1.0'
gem 'omniauth-github', '>= 2.0.0'
gem 'omniauth-gitlab', '>= 3.0.0'
gem 'omniauth-google-oauth2', '>= 0.8.1'
gem 'omniauth-rails_csrf_protection', '>= 1.0.0'
gem 'paperclip'
gem 'rails-observers'
gem 'rb-readline'
gem 'recaptcha', require: 'recaptcha/rails'
# Rails gets support in https://github.com/rails/rails/pull/28297
gem 'rails_same_site_cookie', '>= 0.1.9'

source 'https://rails-assets.org' do
  gem 'rails-assets-jsonlylightbox'
end

gem 'byebug', group: [:development, :test]

group :development do
  gem 'better_errors', '>= 2.7.0'
  gem 'binding_of_caller'
  gem 'capistrano', '~> 3.7'
  gem 'capistrano-bundler', '~> 1.2'
  gem 'capistrano-passenger'
  gem 'capistrano-rails', '~> 1.2'
  gem 'capistrano-rbenv', '~> 2.1'
  # capistrano-sidekiq 1.0.3 is marked as incompatible with Sidekiq 6, but really it is compatible, as long as you use the systemd stuff.
  gem 'capistrano-sidekiq', git: 'https://github.com/rwojnarowski/capistrano-sidekiq.git', ref: '8a8a2edf86dfcdebd69dafc4f96adc55745aecde'
  gem 'capistrano3-delayed-job', '~> 1.0'
  gem 'listen'
  gem 'rubocop'
end

group :profile do
  gem 'ruby-prof'
end

group :test do
  gem 'bundler-audit'
  gem 'capybara', '>= 3.32.2'
  gem 'minitest-around'
  gem 'mocha'
  gem 'selenium-webdriver'
  gem 'webdrivers', '~> 4.3', '>= 4.3.0'
end
