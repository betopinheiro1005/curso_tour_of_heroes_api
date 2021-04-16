source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'rails', '~> 6.1.3'
gem 'puma', '~> 5.0'
gem 'bootsnap', '>= 1.4.4', require: false
gem "active_model_serializers", "~> 0.10.12"
gem "rack-cors", "~> 1.1"

group :development, :test do
  gem 'sqlite3', '~> 1.4'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "faker", "~> 2.17"
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :production do
  gem "pg", "~> 1.2"
end

