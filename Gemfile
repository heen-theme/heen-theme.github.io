source "https://rubygems.org"

# Jekyll 버전 (Ruby 3.4+ 호환)
gem "jekyll", "~> 4.3.0"

# Ruby 3.4+ 필수 gem 추가
gem "csv"
gem "logger"
gem "ostruct"
gem "base64"

# Jekyll 플러그인
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
end

# 플랫폼별 gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 지원
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# 성능 향상 (선택사항)
gem "sassc", "~> 2.4"