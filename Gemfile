source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
#gem "jekyll", "~> 3.8.5"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.0"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
  gem "jekyll-paginate"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Suggestions for a vulnerability of Nokogiri from GitHub. 2024-07-02
gem "nokogiri", ">= 1.16.5"
# Suggestions from Github Dependabot. 2020-08-08
gem "kramdown", ">= 2.3.1"

# Suggestions from Github Dependabot. 2023-08-28
gem "commonmarker", "~> 0.23.10"
gem "activesupport", "~> 6.1.7.5"

# Modification to error "cannot load such file -- webrick (LoadError)"
# when executing "bundle exec jekyll serve". 2024-07-30
gem "webrick" 

## ADD 2025/03/11
## ruby version upgrade (3.1.3 -> 3.4.2) is the reason.
gem 'csv'
gem 'base64'
gem 'bigdecimal'
