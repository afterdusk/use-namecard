source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# gem "namecard"
# If using remote_theme in _config.yml, comment out the gem above. The theme
# will be fetched from the GitHub repo instead of from rubygems

# gem "jekyll", "~> 3.8"
# If you want to use GitHub Pages, comment out the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", "~> 214", group: :jekyll_plugins

# If you have any plugins, put them here!
# group :jekyll_plugins do
#   gem "jekyll-feed", "~> 0.13.0" # not necessary for theme; just an example
# end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

