# frozen_string_literal: true

source "https://rubygems.org"

# Jekyll 核心依賴
gem "jekyll", "~> 4.3"

# 主題相關依賴
gem "jekyll-theme-chirpy", "~> 7.2.4"

# 用於測試的工具
gem "html-proofer", "~> 5.0", group: :test

gem "bundler"

# 時區支持（針對 Windows 平台）
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# 文件監控（針對 Windows 平台）
gem "wdm", "~> 0.2.0", platforms: [:mingw, :x64_mingw, :mswin]
