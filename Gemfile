source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'active_model_serializers'
gem 'knock'
gem 'rails', '~> 5.2.1'
gem 'rails_admin', '~> 1.3'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  gem 'bullet'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-rails'
  gem 'rails_best_practices'
  gem 'reek', "= 4.8.0"
  gem 'rubocop', "= 0.53.0"
  gem 'zero_downtime_migrations'
  gem 'guard' # https://collectiveidea.com/blog/archives/2017/02/09/guard-is-your-friend
  gem 'guard-rspec' # https://chodounsky.net/2015/05/01/how-to-speed-up-your-rspec-workflow/
  gem 'spring-commands-rspec' # https://chodounsky.net/2015/05/01/how-to-speed-up-your-rspec-workflow/
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'database_cleaner'
  gem 'rack-test', require: 'rack/test'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'webmock'
  gem 'timecop'
  gem 'shoulda-callback-matchers'
  gem 'rspec-sidekiq'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
