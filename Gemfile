source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.4'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'carrierwave', '~> 2.1'
gem 'jbuilder', '~> 2.7'
gem 'puma', '~> 4.3'
gem 'rails', '~> 6.0.3', '>= 6.0.3.1'
gem 'rmagick', '~> 4.1', '>= 4.1.2'
gem 'rubocop', '~> 0.88.0', require: false
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'

gem 'spree', '~> 4.1'
gem 'spree_auth_devise', '~> 4.1'
gem 'spree_gateway', '~> 3.7'
gem 'spree_globalize', github: 'spree-contrib/spree_globalize', branch: 'master'
gem 'spree_i18n', github: 'spree-contrib/spree_i18n'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'sqlite3', '~> 1.4'
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :production do
  gem 'pg'
end
