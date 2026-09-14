# rachwalski-budget-lab.github.io

Personal website for Anna Rachwalski, served at
<https://rachwalski-budget-lab.github.io> by GitHub Pages (Jekyll, no theme gem).

## Layout

- `_config.yml` -- site title, URL, author links used across pages.
- `_data/navigation.yml` -- nav bar items.
- `_layouts/default.html` -- only layout: nav bar, content, footer.
- `assets/css/style.css` -- only stylesheet.
- `index.html`, `publications.md`, `experience.md`, `education.md`, `misc.md` -- content.
- `images/about.jpg` -- headshot.

## Editing

Content pages are plain HTML inside front matter. To add a page, copy the front
matter block from an existing one, set `permalink:`, add an entry to
`_data/navigation.yml`.

## Local preview

Needs Ruby:

```
bundle install
bundle exec jekyll serve
```
