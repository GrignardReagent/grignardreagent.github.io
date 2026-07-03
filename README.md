# Xi Yang (Ian) AMRSC

Personal GitHub Pages site for Xi Yang (Ian) AMRSC.

The site is a lightweight Jekyll/GitHub Pages portfolio focused on computational biology, single-cell time-series modelling, stochastic simulations, self-supervised learning, writing, leadership, and contact links.

## Editing Content

Most content can be edited without touching layout HTML or CSS:

- Homepage hero, research sections, contact details: `_data/content.yml`
- Navigation labels and URLs: `_data/navigation.yml`
- Publications and awards: `_data/writing.yml`
- About timeline: `_data/timeline.yml`
- About page prose: `about.md`
- Page titles/descriptions: front matter at the top of `index.md`, `about.md`, `contact.md`, and `404.md`

Layout files live in `_layouts/` and `_includes/`. Visual styles live in `stylesheet.css`.

## Local Preview

GitHub Pages will build the site automatically after pushing to `master`.

For a local Jekyll preview, install Bundler if needed, then run:

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/`.

If you only open the Markdown files directly in a browser, they will not show the final layout; the Jekyll build step renders the finished HTML.
