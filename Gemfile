source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.4.5"

# Bundle edge Rails instead: gem "rails", github: "rails/rails"
# Gói đường ray cạnh thay thế: gem "rails", github: "rails / rails"
gem "rails", "~> 5.2.3"
# Use mysql as the database for Active Record
# Sử dụng mysql làm cơ sở dữ liệu cho Active Record
gem "mysql2", ">= 0.4.4", "< 0.6.0"
# Use Puma as the app server
# Sử dụng Puma làm máy chủ ứng dụng
gem "puma", "~> 3.11"
# Use SCSS for stylesheets
# Sử dụng SCSS cho biểu định kiểu
gem "sass-rails", "~> 5.0"
# Use Uglifier as compressor for JavaScript assets
# Sử dụng Uglifier làm máy nén cho các tài sản JavaScript
gem "uglifier", ">= 1.3.0"
# See https://github.com/rails/execjs#readme for more supported runtimes
# Xem https://github.com/rails/execjs#readme để biết thêm thời gian chạy được hỗ trợ
# MiniRacer cung cấp một cầu nối tối thiểu hai chiều giữa công cụ JavaScript V8 và Ruby.
# đá quý "mini_racer", nền tảng: :ruby
# gem "mini_racer", platforms: :ruby

# Use CoffeeScript for .coffee assets and views
# Sử dụng CoffeeScript cho các tài sản và lượt xem .coffee
# gem "coffee-rails", "~> 4.2"
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# Turbolinks giúp điều hướng ứng dụng web của bạn nhanh hơn. Đọc thêm: https://github.com/turbolinks/turbolinks
gem "turbolinks", "~> 5"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# Xây dựng API JSON dễ dàng. Đọc thêm: https://github.com/rails/jbuilder
gem "jbuilder", "~> 2.5"
# Use Redis adapter to run Action Cable in production
# Sử dụng bộ chuyển đổi Redis để chạy Action Cable trong sản xuất
# gem "redis", "~> 4.0"
# Use ActiveModel has_secure_password
# Sử dụng ActiveModel has_secure_password
# gem "bcrypt", "~> 3.1.7"

# Use ActiveStorage variant
# Sử dụng biến thể ActiveStorage
# gem "mini_magick", "~> 4.8"

# Use Capistrano for deployment
# Sử dụng Capistrano để triển khai
# gem "capistrano-rails", group: :development

# Reduces boot times through caching; required in config/boot.rb
# Giảm thời gian khởi động thông qua bộ nhớ đệm; bắt buộc trong config / boot.rb
gem "bootsnap", ">= 1.1.0", require: false

group :development, :test do
  # Call "byebug" anywhere in the code to stop execution and get a debugger console
  # Gọi "byebug" bất cứ nơi nào trong mã để dừng thực thi và nhận bảng điều khiển trình gỡ lỗi
  # gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "pry", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling "console" anywhere in the code.
  # Truy cập bảng điều khiển tương tác trên các trang ngoại lệ hoặc bằng cách gọi "console" ở bất kỳ đâu trong mã.
  gem "web-console", ">= 3.3.0"
  # The Listen gem listens to file modifications and notifies you about the changes.
  gem "listen", ">= 3.0.5", "< 3.2"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # Spring tăng tốc độ phát triển bằng cách giữ cho ứng dụng của bạn chạy trong nền. Đọc thêm: https://github.com/rails/spring
  gem "spring"
  # This gem makes Spring watch the filesystem for changes using Listen rather than by polling the filesystem.
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  # Thêm hỗ trợ để kiểm tra hệ thống Capybara và trình điều khiển selen
  # Capybara helps you test web applications by simulating how a real user would interact with your app.
  # Capybara giúp bạn kiểm tra các ứng dụng web bằng cách mô phỏng cách người dùng thực sự tương tác với ứng dụng của bạn.
  gem "capybara", ">= 2.15"
  # Selenium is an umbrella project encapsulating a variety of tools and libraries enabling web browser automation.
  gem "selenium-webdriver"
  # Easy installation and use of chromedriver to run system tests with Chrome
  # NOTICE: This gem is out of support as of 2019-03-31
  # gem "chromedriver-helper"
  # Run Selenium tests more easily with install and updates for all supported webdrivers.
  # Chạy thử nghiệm Selenium dễ dàng hơn với cài đặt và cập nhật cho tất cả các máy chủ web được hỗ trợ.
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Windows không bao gồm các tệp zoneinfo, vì vậy hãy đóng gói đá quý dữ liệu tzinfo
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# ------------------------------------------------------------------
# By rails tutorial

# Bundle edge Rails instead: gem "rails", github: "rails/rails"
gem "bcrypt", "~> 3.1.7"
#gem "faker", "1.7.3"
# Use this for pagination of users on index page
gem "will_paginate", "3.1.5"
gem "bootstrap-will_paginate", "1.0.0"
gem "bootstrap-sass", "3.3.7"

# Use this to handle image uploading (13.4.1)
gem "carrierwave",             "1.1.0"
gem "mini_magick",             "4.7.0"
gem "fog",                     "1.40.0"

# Other

gem "bcrypt-ruby"

# test

gem "rails-controller-testing", "1.0.2"
gem "minitest-reporters", "1.1.14"
gem "guard", "2.13.0"
gem "guard-minitest", "2.4.4"

# Other

gem "jquery-rails"

# ------------------------------------------------------------------
# Authentication - begin by Amari
 #gem "omniauth"
 #gem "omniauth-ldap"
 gem "devise"
 gem "devise_ldap_authenticatable"

# Static program analysis
 gem "rubocop-rails"
 #gem "rails_best_practices"

# paser
gem "roo"

# Usefuls for api
gem "active_model_serializers"

# Implementing multi tanant
gem "apartment"

#Custom helper
gem "enum_help"

# ------------------------------------------------------------------
# By team Ruby 2NF

gem "factory_bot"
gem "ffaker"

gem "rspec-rails"
gem "shoulda-matchers"

# ------------------------------------------------------------------
# By team Ruby Mulaco
gem "pg"
gem "omniauth-facebook"
gem "activerecord-reset-pk-sequence"
gem "kaminari"
gem "ransack"
#gem 'i18n'
gem "breadcrumbs_on_rails"

# ------------------------------------------------------------------
# By team Ruby Ruby Development

# ------------------------------------------------------------------
# By Dat

gem "font-awesome-rails"
gem "config"
gem "ckeditor"

gem "cocoon"
gem "toastr-rails"
gem "dotenv-rails"
gem "hirb"

gem "momentjs-rails"
gem "sidekiq"
gem "rails_bootstrap_sortable"

# By Dat - test + development
gem "factory_bot_rails"
gem "better_errors"
gem "guard-rspec"
gem "database_cleaner"
gem "brakeman"
gem "jshint"
gem "bundler-audit"
gem "rubocop" #Wish
gem "rubocop-checkstyle_formatter"
gem "scss_lint_reporter_checkstyle"

gem "reek"
gem "railroady"

# By Dat - test
gem "simplecov"
gem "simplecov-rcov"
gem "simplecov-json"

# By Dat - production
gem "rails_12factor", "0.0.2"
