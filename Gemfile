source 'https://rubygems.org'

gem 'rails'

gem 'mysql2'
gem 'redis'
gem 'mongo'
gem 'mongoid'
gem 'mongoid_location'
gem 'bson_ext'

# 资源模板引擎
gem 'sass-rails'
gem 'coffee-rails'
gem 'uglifier'
gem 'cells'

# 缓存系统
gem 'redis-activesupport'
gem 'redis-objects'

# 搜索引擎
gem 'tire'

# js组件
gem 'jquery-rails', '2.0.2'

# 异步和定时任务
gem 'resque'
gem 'resque-scheduler'

# 文件和图片处理
gem 'mini_magick'
gem 'carrierwave'
gem 'carrierwave-aliyun'
gem "carrierwave-mongoid", :git => "git://github.com/jnicklas/carrierwave-mongoid.git", :branch => "mongoid-3.0"

# 用户登录
gem 'devise'
gem 'omniauth-twitter'
gem 'omniauth'
gem 'omniauth-weibo-oauth2'
gem 'weibo'
gem 'weibo2'
gem 'weibo2_plugins'

# 辅助组件
gem 'rails_config'
gem 'acts_as_list'
gem 'state_machine'
gem 'will_paginate'
gem 'will_paginate_mongoid'
gem 'typhoeus'
gem 'nokogiri'
gem 'rest-client'
gem "therubyracer"
gem "less-rails"
gem "twitter-bootstrap-rails"
gem 'will_paginate-bootstrap'
gem 'quiet_assets'  # 禁用assets log

# 开发环境
group :development do
  gem 'rails3-generators'
  gem 'spork', '>= 0.9.0'
  gem 'capistrano'
  gem 'pry'
  gem 'pry-nav'
end

# 开发测试环境共用
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'factory_girl_rails'#, require: false  # 修复对model的preload
end