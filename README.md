# Tongxin Zhou · Academic homepage

A bilingual academic site built with Jekyll for GitHub Pages. The English homepage lives at `/` and the Chinese homepage at `/zh/`. Both read from `_data/academic.yml`, as do the academic CV pages.

## Edit content

- `_data/academic.yml` holds the biography, research directions, publications, projects, education, awards, and service. Use `en` and `zh` for localized text. Use the official status and links for each publication.
- `assets/css/academic.css` holds the shared site styling.
- `_config.yml` holds the GitHub Pages project path and public contact links.

## Preview locally

From a Ruby environment with Bundler installed, run:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

Open `http://127.0.0.1:4000/tongxinzhou.github.io/`. To build without starting a server, run `bundle exec jekyll build`.
