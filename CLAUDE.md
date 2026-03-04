# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Jekyll-based academic portfolio site (seokwon99.github.io) that also serves as the `jekyll-theme-minimal` gem (v0.2.0). Hosted on GitHub Pages.

## Common Commands

```bash
# Setup
script/bootstrap                # Install dependencies (bundler + bundle install)

# Development
bundle exec jekyll serve        # Local preview at localhost:4000

# Build
bundle exec jekyll build        # Generate _site/ directory

# Full CI pipeline (build + htmlproofer + rubocop + w3c validation + gem build)
script/cibuild

# Individual checks
bundle exec rubocop -D --config .rubocop.yml    # Ruby linting
bundle exec htmlproofer ./_site --check-html --check-sri  # HTML validation
script/validate-html                             # W3C HTML/CSS validation
```

## Architecture

- **_layouts/**: HTML templates — `default.html` (main layout with sidebar + content) and `post.html` (blog posts)
- **_includes/**: Partials for `<head>` customization and Google Analytics
- **_sass/**: Theme styles — `jekyll-theme-minimal.scss` is the main stylesheet; `fonts.scss`, `rouge-github.scss` for syntax highlighting
- **assets/**: Static files (CSS entry point at `assets/css/style.scss`, JS, images, fonts)
- **script/**: Build automation (bootstrap, cibuild, validate-html, release)
- **index.md**: Homepage content (academic CV/portfolio)

## Key Patterns

- Pages are Markdown files with YAML front matter, processed by Jekyll/Liquid templating
- Custom CSS must go through `assets/css/style.scss` which imports the theme via `@import "jekyll-theme-minimal"`
- Site config lives in `_config.yml` (title, description, logo, Google Analytics ID, plugins)
- Layout uses fixed 270px left sidebar + 500px content area with responsive breakpoints at 960/720/480px
- The project is both a live site and a distributable gem defined in `jekyll-theme-minimal.gemspec`
- Ruby style follows rubocop-github conventions (`.rubocop.yml`)
