source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'cssbundling-rails'
gem 'devise', '~> 4.8', '>= 4.8.0'
gem 'friendly_id', '~> 5.4'
gem 'hotwire-rails'
gem 'image_processing'
gem 'jsbundling-rails'
gem 'madmin'
gem 'name_of_person', '~> 1.1'
gem 'noticed', '~> 1.4'
gem 'omniauth-facebook', '~> 8.0'
gem 'omniauth-github', '~> 2.0'
gem 'omniauth-twitter', '~> 1.4'
gem 'pretender', '~> 0.3.4'
gem 'pundit', '~> 2.1'
gem 'sidekiq', '~> 6.2'
gem 'sitemap_generator', '~> 6.1'
gem 'whenever', require: false
gem 'responders', github: 'heartcombo/responders', branch: 'main'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem "faker"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails"
end

group :development do
  gem 'listen'
  gem 'spring'
  gem "bullet"
  gem "pgreset"
  gem "web-console"
  gem 'rack-mini-profiler'
end

group :test do
  gem "database_cleaner"
  gem "factory_bot_rails"
  gem "rails-controller-testing"
  gem "shoulda-callback-matchers"
  gem "shoulda-matchers"
  gem "simplecov"
  gem "timecop"
end
