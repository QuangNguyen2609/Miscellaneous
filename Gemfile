GEM
  remote: https://rubygems.org/
  specs:
    addressable (2.8.0)
      public_suffix (>= 2.0.2, < 5.0)
    colorator (1.1.0)
    concurrent-ruby (1.1.10)
    em-websocket (0.5.3)
      eventmachine (>= 0.12.9)
      http_parser.rb (~> 0)
    eventmachine (1.2.7)
    ffi (1.15.5)
    forwardable-extended (2.6.0)
    http_parser.rb (0.8.0)
    i18n (0.9.5)
      concurrent-ruby (~> 1.0)
    jekyll (3.9.2)
      addressable (~> 2.4)
      colorator (~> 1.0)
      em-websocket (~> 0.5)
      i18n (~> 0.7)
      jekyll-sass-converter (~> 1.0)
      jekyll-watch (~> 2.0)
      kramdown (>= 1.17, < 3)
      liquid (~> 4.0)
      mercenary (~> 0.3.3)
      pathutil (~> 0.9)
      rouge (>= 1.7, < 4)
      safe_yaml (~> 1.0)
    jekyll-feed (0.16.0)
      jekyll (>= 3.7, < 5.0)
    jekyll-sass-converter (1.5.2)
      sass (~> 3.4)
    jekyll-seo-tag (2.8.0)
      jekyll (>= 3.8, < 5.0)
    jekyll-watch (2.2.1)
      listen (~> 3.0)
    kramdown (2.3.2)
      rexml
    kramdown-parser-gfm (1.1.0)
      kramdown (~> 2.0)
    liquid (4.0.3)
    listen (3.7.1)
      rb-fsevent (~> 0.10, >= 0.10.3)
      rb-inotify (~> 0.9, >= 0.9.10)
    mercenary (0.3.6)
    minima (2.5.1)
      jekyll (>= 3.5, < 5.0)
      jekyll-feed (~> 0.9)
      jekyll-seo-tag (~> 2.1)
    pathutil (0.16.2)
      forwardable-extended (~> 2.6)
    public_suffix (4.0.7)
    rb-fsevent (0.11.1)
    rb-inotify (0.10.1)
      ffi (~> 1.0)
    rexml (3.2.5)
    rouge (3.28.0)
    safe_yaml (1.0.5)
    sass (3.7.4)
      sass-listen (~> 4.0.0)
    sass-listen (4.0.0)
      rb-fsevent (~> 0.9, >= 0.9.4)
      rb-inotify (~> 0.9, >= 0.9.7)
    thread_safe (0.3.6)
    tzinfo (1.2.9)
      thread_safe (~> 0.1)
    tzinfo-data (1.2022.1)
      tzinfo (>= 1.0.0)
    wdm (0.1.1)
    webrick (1.7.0)

PLATFORMS
  aarch64-linux-musl
  arm64-darwin-21

DEPENDENCIES
  http_parser.rb (~> 0.6.0)
  jekyll (~> 3.9.2)
  jekyll-feed (~> 0.6)
  kramdown-parser-gfm
  minima (~> 2.0)
  tzinfo (~> 1.2)
  tzinfo-data
  wdm (~> 0.1.0)
  webrick (~> 1.7)

BUNDLED WITH
   2.3.10

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]