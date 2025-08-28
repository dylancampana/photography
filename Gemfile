source "https://rubygems.org"

# GitHub Pages compatible gems
gem "github-pages", "~> 232", group: :jekyll_plugins

# Jekyll version compatible with GitHub Pages
gem "jekyll", "~> 3.10.0"

# Required for local development on Ruby 3.0+
gem "webrick", "~> 1.8"

# Optional gems for better development experience
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-github-metadata"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]