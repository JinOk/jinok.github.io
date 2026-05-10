# jinok.github.io

Personal homepage of **Jin Ok Yang, Ph.D.** — Principal Research Scientist at the
Korea Bioinformation Center (KOBIC), KRIBB.

Built with [Jekyll](https://jekyllrb.com) and hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then visit <http://localhost:4000>.

## Editing content

- **Profile copy / hero / sections** → `index.html`
- **Publications** → `_data/publications.yml`
  - Set `featured: true` to surface a paper in the highlighted cards.
  - Set `recent: true` to include a paper in the *Recent* tab.
- **Site metadata** → `_config.yml`
- **Styling** → `assets/css/style.scss`
- **Layout / nav / footer** → `_layouts/default.html`
