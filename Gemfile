# frozen_string_literal: true

source "https://rubygems.org"

# The `github-pages` gem pins Jekyll and every plugin to exactly the versions
# GitHub Pages runs, so `bundle exec jekyll build` locally produces the same
# site the deployed build does. Bump this only when GitHub does:
# https://pages.github.com/versions/
gem "github-pages", "~> 232", group: :jekyll_plugins

# Not pulled in by github-pages, and needed on Ruby 3.x.
gem "webrick", "~> 1.8"

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
