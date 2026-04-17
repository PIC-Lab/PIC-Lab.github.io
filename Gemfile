source 'https://rubygems.org'
group :jekyll_plugins do
    gem 'jekyll'
    gem 'jekyll-archives'
    gem 'jekyll-diagrams'
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-imagemagick'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-link-attributes'
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    # JavaScript runtime for ExecJS (used by jekyll-minifier).
    # On Apple Silicon macOS, `mini_racer`/`libv8-node` frequently fails to build.
    # In that case, prefer using Node.js as the JS runtime and skip this gem.
    gem 'mini_racer', '~> 0.6.4' unless RUBY_PLATFORM.match?(/darwin/i) && RUBY_PLATFORM.match?(/arm64/i)
    gem 'unicode_utils'
    gem 'webrick'
    gem 'ffi', '< 1.17'
end
group :other_plugins do
    gem 'httparty'
    gem 'feedjira'
end
