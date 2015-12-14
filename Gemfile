source 'https://rubygems.org'
  
  gem 'rails', '4.2.4'
  gem 'sass-rails', '~> 5.0'
  gem 'bootstrap-sass', '~> 3.3.6'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.1.0'
  gem 'coffee-script-source'
  gem 'jquery-rails'
  gem 'turbolinks'
  gem 'jbuilder', '~> 2.0'
  gem 'sdoc', '~> 0.4.0', group: :doc
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
  gem 'devise'
  gem 'bcrypt', '~> 3.1', '>= 3.1.10'
  gem 'simple_form' #rails generate simple_form:install #rails generate simple_form:install --bootstrap
  # = simple_form_for(@user, html: { class: 'form-horizontal' }) do |form|  classes, '.form-horizontal' or '.form-inline', as the following:
  gem 'composite_primary_keys', '~> 8.1', '>= 8.1.1'
  gem "cocoon" #rails g cocoon:install #add the following below the default javascripts: = javascript_include_tag :cocoon
  gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'
  #rails generate bootstrap:install static
  group :development, :test do
    # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end
  
  group :development do
  gem 'web-console', '~> 2.0'
  gem 'sqlite3'
  gem 'spring'
end
  
  group :production do
  gem 'rails_12factor'
  gem 'pg'
end

#rails generate simple_form:install
#rails generate simple_form:install --bootstrap
#add the following below the default javascripts: = javascript_include_tag :cocoon
#  Inside your views, use the 'simple_form_for' with one of the Bootstrap form
#  classes, '.form-horizontal' or '.form-inline', as the following:
#
#    = simple_form_for(@user, html: { class: 'form-horizontal' }) do |form|