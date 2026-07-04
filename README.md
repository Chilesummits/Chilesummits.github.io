# chilesummits.github.io

Erik Sandvig's academic website, built with Jekyll on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and hosted on GitHub Pages.

## Site structure

- `_config.yml` — site-wide settings (name, bio, social links)
- `_pages/about.md` — homepage bio
- `_pages/cv.md` — CV
- `_publications/` — one Markdown file per publication (see existing theme docs for front matter format)
- `_posts/` — blog posts, if any
- `images/profile.png` — sidebar avatar (replace with your own photo)

## Running locally

1. Install Ruby, Bundler, and Node (macOS: `brew install ruby node && gem install bundler`)
2. `bundle install`
3. `bundle exec jekyll serve -l -H localhost`
4. Open http://localhost:4000

Changes to Markdown/HTML content reload automatically; changes to `_config.yml` require restarting Jekyll.

## Deploying

Push to the `main` branch of `chilesummits/chilesummits.github.io` — GitHub Pages rebuilds and publishes automatically at https://chilesummits.github.io.
