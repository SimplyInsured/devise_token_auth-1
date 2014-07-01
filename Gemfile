source "https://rubygems.org"

# Declare your gem's dependencies in devise_token_auth.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'

group :development do
  gem "pry"
  gem "figaro"
  gem 'omniauth-github',        :git => 'git://github.com/intridea/omniauth-github.git'
  gem 'omniauth-facebook',      :git => 'git://github.com/mkdynamic/omniauth-facebook.git'
  gem 'omniauth-google-oauth2', :git => 'git://github.com/zquestz/omniauth-google-oauth2.git'
  gem 'rack-cors',              :require => 'rack/cors'
  gem 'attr_encrypted'
end