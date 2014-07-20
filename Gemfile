source 'https://rubygems.org'
ruby '2.1.2'
gem 'rails', '4.1.4'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'bootstrap-sass', '>= 3.0.0.0'
gem 'figaro'
gem 'haml-rails'
gem 'pg'
gem 'd3-rails'

group :doc do
  gem 'sdoc', '~> 0.4.0', require: false
end
group :development do
  gem 'spring'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :rbx]
  gem 'html2haml'
  gem 'quiet_assets'
  gem 'rails_layout'
  gem 'wkhtmltopdf-binary'
end 

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end

group :production do
  gem 'unicorn'
  gem 'rails_12factor'
  gem "wkhtmltopdf-heroku", :git => 'git://github.com/camdez/wkhtmltopdf-heroku.git'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

