# frozen_string_literal: true

source "https://rubygems.org"

# Jekyll 버전
gem "jekyll", "~> 4.4.1"

# Jekyll 플러그인들
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
end

# Windows 및 JRuby 지원
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 성능 향상
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby 지원
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]