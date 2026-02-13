# Hari Govindarajan - Personal Site

This site is built with Jekyll and a Hyde-style layout customized for resume and photography content.

## Local preview (no commit required)

```bash
cd /Users/harigovindarajan/Downloads/harigovindarajan.github.io

# One-time setup
brew install rbenv ruby-build
rbenv install 3.2.4
rbenv local 3.2.4
gem install bundler

# Install dependencies in this repo only
bundle config set --local path vendor/bundle
bundle install

# Run local site
bundle exec jekyll serve --livereload
```

Open `http://127.0.0.1:4000`.

## Quick verification

```bash
git status --short
git diff _config.yml public/css/custom.css
```
