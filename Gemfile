source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.11'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.5'
  gem 'coffee-rails', '~> 3.2.2'
  gem 'bootstrap-sass'
  gem 'bootstrap-addons-rails'
  gem 'chosen-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
  gem 'asset_sync'
end

gem "jquery-rails"
gem "jquery-fileupload-rails"
gem "placeholder"

gem 'haml'
gem 'coffee-filter'
gem 'simple_form'
gem 'grape'
gem 'devise'
gem 'cancan'
gem 'fog'

gem 'mongoid'
gem 'mongoid-paperclip'

gem 'mongoid_slug'
gem 'tire'
gem 'kaminari'

# API
gem 'doorkeeper'
gem 'rabl'

group :development do
end

group :production, :staging do
  gem 'aws-sdk'
  gem 'unicorn'
end

group :development, :test do
  gem 'pry'
  gem 'pry-remote'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'json_spec'
  gem 'rspec-rails'
  gem 'mongoid-rspec'
  gem 'sextant'
end
