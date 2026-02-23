source "https://rubygems.org"

# Jekyll version compatible with GitHub Pages
gem "jekyll", "~> 4.3"

# GitHub Pages plugins
gem "jekyll-feed", "~> 0.17"
gem "jekyll-seo-tag", "~> 2.8"
gem "jekyll-remote-theme", "~> 0.4"

# Other useful plugins
gem "webrick", "~> 1.8" # Required for Ruby 3.0+

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
