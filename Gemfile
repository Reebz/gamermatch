source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '4.0.1'

# Rails defaults
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'thin'

# Rails authentication
gem 'cancan'
gem 'devise'
gem 'rolify'

# rails-bootstrap-project
gem 'activerecord-tableless'
gem 'bootstrap-sass', '~> 2.3.2.2'
gem 'figaro'
gem 'google_drive'
gem 'high_voltage'
gem 'simple_form'

group :development do
  gem 'sqlite3'
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :rbx]
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rails_layout'
end

group :test do
	gem 'rspec-rails'
	gem 'database_cleaner'
	gem 'email_spec'
	gem 'launchy'
	gem 'cucumber-rails', :require=>false
	gem 'capybara'
	gem 'factory_girl_rails'
end

group :production do
	gem 'pg'
	gem 'rails_on_heroku'
	gem 'rails_12factor'
end