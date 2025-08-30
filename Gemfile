source "https://rubygems.org"

# Use the latest stable Jekyll version
gem "jekyll", "~> 3.9.3"

# Latest GitHub Pages (includes many security updates)
gem "github-pages", "~> 228", group: :jekyll_plugins

# Your theme
gem "minima", "~> 2.5"

# Your plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
end

# Critical security updates - force latest versions
gem "nokogiri", ">= 1.14.3"
gem "activesupport", ">= 6.0.6.1"
gem "addressable", ">= 2.8.1"
gem "tzinfo", ">= 1.2.10"
gem "webrick", ">= 1.8.0"

# Additional security gems
gem "rack", ">= 2.2.0"
gem "rack-protection", ">= 2.2.0"

# Platform-specific gems
platforms :windows, :jruby do
  gem "tzinfo-data"
end

platforms :windows do
  gem "wdm", "~> 0.1.1"
end