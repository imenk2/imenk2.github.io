# frozen_string_literal: true

# 指定 gem 的来源
source "https://rubygems.org"

# 明确指定 Jekyll 版本
gem "jekyll", "~> 4.3"

# 明确指定主题
gem "jekyll-theme-minimal", "~> 0.2.0"

# 不依赖 sass-embedded 的旧版本，
# 它使用更稳定的 sassc 编译器
gem "jekyll-sass-converter", "2.2.0"

# 为 Ruby 3.0+ 环境添加 Jekyll 运行必需的 web server
gem "webrick"

gem 'bigdecimal'
gem 'logger'

# 网站插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag"
end