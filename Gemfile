# frozen_string_literal: true

#############################
######### DEFAULT ###########
#############################

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'puma', '~> 3.12'
gem 'rails', '~> 5.2.3'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

##############################
####### SETUP GEMS ###########
##############################

gem 'active_model_serializers', '~> 0.10.2'
gem 'apartment'
gem 'bcrypt', '~> 3.1.7'
gem 'faker'
gem 'figaro'
gem 'geocoder', '~> 1.5', '>= 1.5.1'
gem 'jwt'
gem 'pg', '>= 0.18', '< 2.0'
gem 'rack-attack'
gem 'rack-cors'
gem 'ransack'
gem 'simple_command'
gem 'kaminari'

##############################
####### UPLOAD IMAGE #########
##############################

gem 'carrierwave'
gem 'cloudinary'
gem 'mini_magick'