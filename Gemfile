# Specify the source for Ruby gems
source "https://rubygems.org"

# Theme for the Jekyll site
gem "jekyll-theme-chirpy", "~> 7.1", ">= 7.1.1"

# Specify versioned dependencies
gem "html-proofer", "~> 5.0", group: :test

# Jekyll setup
# Manage which Jekyll version is used to run the site
gem "jekyll", "~> 4.3.4"

# Optional: Uncomment this line if using GitHub Pages to manage dependencies automatically
# gem "github-pages", group: :jekyll_plugins

# Jekyll Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"        # Adds RSS feed support
  gem "jekyll-sitemap", "~> 1.4"      # Automatically generates a sitemap.xml
  gem "jekyll-paginate"               # Adds pagination support
  gem "jekyll-seo-tag"                # Adds SEO-related tags to the site
end

# Platform-Specific Gems

# For Windows (mingw, x64_mingw, mswin), include timezone data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance improvement for directory watching on Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby-specific setup: lock `http_parser.rb` to `v0.6.x`
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
