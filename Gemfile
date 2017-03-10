source 'https://rubygems.org'

ruby '2.3.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'
# Work around deprecated functions - https://github.com/rails/sass-rails/issues/381#issuecomment-234334012
gem 'sprockets', '3.6.3'
# Use MySQL2 as the database for Active Record
gem 'mysql2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Bootstrap in Sass format
gem 'bootstrap-sass'
# Font Awesome
gem 'font-awesome-rails'
# Form builder using Twitter Bootstrap 3+
gem 'bootstrap_form'
# Using Bootstrap Datepicker
gem 'bootstrap-datepicker-rails'
# Moment js required by bootstrap3 datetime picker
gem 'momentjs-rails', '>= 2.9.0'
# Using Bootstrap3 datetime picker
gem 'bootstrap3-datetimepicker-rails', '~> 4.17.37'
# Use to validate dates
gem 'validates_timeliness', '~> 4.0', '>= 4.0.2'
# Use Kaminari for pagination
gem 'kaminari'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
gem 'unicorn'

# Store stuff in Redis, including the Rails cache
gem "redis-rails"

# Use Resque as the queue server
gem 'resque'
gem 'resque-scheduler'
gem 'active_scheduler'

# A scheduler process to replace cron
gem 'clockwork'

# Using Flexirest for Elastisearch communication
gem 'flexirest'

# Use RedCarpet for parsing Markdown to HTML
gem 'redcarpet'

# Include the auto_link method which was deprecated/removed in Rails 3.1
gem 'rails_autolink'

# Natural date expression parsing
gem "chronic"

# Slack API
gem 'slack-ruby-client'

# Gem for websockets for Slack
gem 'celluloid-io', require: false

# Mustache templating for JavaScript
gem 'mustache-js-rails'

# Prawn for PDF Creation
gem 'prawn'

# Prawn Rails for rails view integration
gem 'prawn_rails'

# Paperclip for attaching files to tickets
gem 'paperclip'
#
# AASM for state machine functionality
gem 'aasm'

# Add Mouse Trap for keyboard shortcuts
gem 'mousetrap-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Load the .env file in development/test (but not production)
  gem 'dotenv-rails'

  # Shut up all the asset lines in Development logs
  gem "quiet_assets"

end

group :test do
  # Guard Spring integration for faster tests
  gem 'guard-spring'
  gem 'spring-commands-rspec'
  #
  # Use RSpec as the testing framework
  gem 'rspec-rails'

  # Use FactoryGirl for model factories
  gem 'factory_girl_rails'

  # Use simplecov to see how much of the code base is tested
  gem 'simplecov', require: false

  # Use Guard for automated RSpec test runs
  gem 'guard-rspec', require: false
  gem 'terminal-notifier-guard'

  # Use Capybara for integration tests
  gem 'capybara'

  gem "fakeredis", require: "fakeredis/rspec"

  # Poltergeist for headless JS testing
  gem "poltergeist"

  gem 'database_cleaner'

  # Helper Gem to select from select2 in tests
  gem 'capybara-select2', git: 'https://github.com/leonardofalk/capybara-select2.git'
end

group :development do
  # Use Letter Opener to open emails in a browser
  gem 'letter_opener'

  # Console output and debug
  gem 'pry-rails', '~> 0.3.4'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
