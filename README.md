# personal-website

Personal website built with Jekyll, deployed via GitHub Pages.

Live at: https://s-huang23.github.io/ (once Pages is enabled — see below)

## Enable GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose branch `main`, folder `/ (root)`, then **Save**.
5. The site builds automatically and is live in a minute or two at the URL above.

## Local development

Requires [Ruby](https://www.ruby-lang.org/) and [Bundler](https://bundler.io/).

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/

## Editing content

- **About page**: [index.md](index.md)
- **Resume**: PDF at [assets/files/Si-Qin-Huang-Resume.pdf](assets/files/Si-Qin-Huang-Resume.pdf), embedded/downloadable via [resume.md](resume.md) — replace the PDF file to update
- **Contact / site info**: [_config.yml](_config.yml) (`author` block — name, email, github, linkedin, location); social icons render from [_includes/social.html](_includes/social.html)
- **Styling**: [assets/css/main.css](assets/css/main.css) — colors, type scale, and the reading-width measure are all CSS custom properties at the top of the file
