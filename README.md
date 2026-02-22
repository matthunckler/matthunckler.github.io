# matthunckler.github.io

Personal site and blog for Matt Hunckler, built with Jekyll and hosted on GitHub Pages.

## Local development

### Prerequisites
- Ruby (use the version in `.ruby-version`)
- Bundler

### Setup
```bash
bundle install
```

### Run locally
```bash
bundle exec jekyll serve
```

Site will be available at `http://127.0.0.1:4000`.

## Build
```bash
bundle exec jekyll build
```

The generated site is written to `_site/`.

## Content structure
- `_posts/`: Blog posts using `YYYY-MM-DD-title.markdown`
- `about.md`: About page
- `_config.yml`: Site-wide Jekyll configuration

## Deployment
This repository is intended to be served by GitHub Pages.
