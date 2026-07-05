# chilesummits.github.io

Erik Sandvig's academic website, built with [Hugo](https://gohugo.io) on the [HugoBlox Academic CV](https://github.com/HugoBlox/theme-academic-cv) template and hosted on GitHub Pages.

## Site structure

- `config/_default/params.yaml` — site-wide settings (name, tagline, colors, header/footer)
- `config/_default/menus.yaml` — top navigation
- `content/_index.md` — homepage sections (bio, projects, publications, news)
- `content/experience.md` — CV/experience page (pulls from `data/authors/me.yaml`)
- `content/publications/` — one folder per publication
- `content/projects/` — one folder per research project (shown as cards)
- `content/blog/` — news/updates, shown in the homepage "Recent News" section
- `data/authors/me.yaml` — bio, education, experience, skills, social links
- `assets/media/authors/me.<ext>` — profile photo (add your own; none is committed yet)

## Running locally

1. Install [Hugo Extended](https://gohugo.io/installation/), [Go](https://go.dev) (for Hugo Modules), and [pnpm](https://pnpm.io)
2. `pnpm install`
3. `pnpm dev` (runs `hugo server --disableFastRender`)
4. Open http://localhost:1313

## Deploying

Push to `main` on `chilesummits/chilesummits.github.io` — a GitHub Actions workflow (`.github/workflows/deploy.yml`) builds the site with Hugo and publishes it to GitHub Pages at https://chilesummits.github.io.
