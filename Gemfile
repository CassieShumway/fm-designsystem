source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

# gem 'github-pages', versions['github-pages']
gem 'github-pages', group: :jekyll_plugins

gem 'jekyll', '3.3.1'

group :jekyll_plugins do
  gem 'jekyll-sitemap', '0.11.0'
  gem 'jekyll-seo-tag', '2.0.0'
  gem 'jekyll-feed', '0.7.2'
end