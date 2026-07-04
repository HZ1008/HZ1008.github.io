source "https://rubygems.org"

gem "jekyll", "~> 4.4"

# Windows 时区数据
gem "tzinfo-data", platforms: [:windows, :jruby]

# Ruby 4.0 需要手动引入的标准库
gem "csv"
gem "bigdecimal"
gem "ostruct"
gem "mutex_m"

# 注释掉 wdm，与 Ruby 4.0 不兼容
# gem "wdm", "~> 0.1.0" if Gem.win_platform?

# 插件（与 _config.yml 保持一致）
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
  gem "jemoji"
  # gem "hawkins"  # 不兼容 Jekyll 4，用 jekyll serve --livereload 代替
end
