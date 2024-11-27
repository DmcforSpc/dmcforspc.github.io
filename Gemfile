# frozen_string_literal: true  # 强制所有字符串字面量不可变，提高性能，减少内存使用

source "https://rubygems.org"  # 指定 Ruby gems 的源为官方的 rubygems.org

# 主题配置，安装 Jekyll 的 Chirpy 主题，版本要求 >= 7.1.1 且 <= 7.1.x
gem "jekyll-theme-chirpy", "~> 7.1", ">= 7.1.1"

# html-proofer 用于检查 HTML 文件的有效性，安装到测试组中
gem "html-proofer", "~> 5.0", group: :test

# 针对 Windows 和 JRuby 平台的特定依赖
platforms :mingw, :x64_mingw, :mswin, :jruby do
  # tzinfo 是时区信息库，指定其版本为 >= 1 且 < 3
  gem "tzinfo", ">= 1", "< 3"
  # tzinfo-data 提供 tzinfo 的数据文件
  gem "tzinfo-data"
end

# wdm 是 Windows 下的文件监控库，仅在 Windows 平台下安装
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# logger 提供日志记录功能，默认输出到控制台
gem 'logger'

# csv 提供 CSV 文件的解析和生成支持
gem 'csv'

# base64 用于编码和解码 Base64 格式数据
gem 'base64'
