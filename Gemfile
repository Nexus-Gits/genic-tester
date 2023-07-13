source "https://rubygems.org"

gem "jekyll"

group :jekyll_plugins do
  gem "jemoji"
  gem "jekyll-postcss"
  gem "jekyll-minifier"
  gem "jekyll-archives"
  gem "jekyll-hostname"
  gem "jekyll-paginate-v2"
  gem "jekyll-loading-lazy"
  gem "jekyll-redirect-from"
  gem "jekyll-auto-authors"
  gem "jekyll-url-metadata"
  gem "jekyll-include-cache"
end

# Performance-booster for watching directories on Windows
gem "wdm", :platforms => [:mingw, :x64_mingw, :mswin]

gem "dotenv"
gem "webrick"

# Lock jekyll-sass-converter to 2.x on Linux-musl
if RUBY_PLATFORM =~ /linux-musl/
  gem "jekyll-sass-converter", "~> 2.0"
end
