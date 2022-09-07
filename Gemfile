# frozen_string_literal: true

source "https://mirrors.aliyun.com/rubygems/"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"

gem "webrick", "~> 1.7"
gem "github-pages"