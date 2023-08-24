source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "activerecord-import"
gem "bootsnap", require: false
gem "cssbundling-rails"
gem "devise"
gem 'dotenv-rails', groups: %i[development test]
gem "jbuilder"
gem "jsbundling-rails"
gem "jsonapi-serializer"
gem "importmap-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem 'pundit', '~> 2.3', '>= 2.3.1'
gem "rails", "~> 7.0.5"
gem 'redis', '~> 5.0', '>= 5.0.6'
gem 'sassc-rails'
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "factory_bot_rails"
  gem 'faker'
  gem "pry-rails"
  gem 'rspec-rails', '~> 6.0', '>= 6.0.3'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  gem 'shoulda-matchers', '~> 5.3'
end
