# CharlisCurley.github.io

Source for my personal site, built with Jekyll and hosted on GitHub Pages.

## Structure

- `index.md` — homepage
- `projects.md` — Power BI and data project write-ups
- `writing.md` — lists all blog posts (don't edit content here, it's generated from `_posts/`)
- `_posts/` — blog posts, one file per post, named `YYYY-MM-DD-title.md`
- `assets/cv.pdf` — CV file linked from the homepage (not included yet, add your own)
- `_config.yml` — site settings, title, navigation

## Adding a blog post

Create a new file in `_posts/` named `YYYY-MM-DD-title.md`:

```
---
layout: post
title: "Your title here"
date: YYYY-MM-DD
---

Your content in Markdown.
```

## Adding a project

Edit `projects.md` and add a new section following the existing pattern.

## Previewing locally (optional)

Requires Ruby and Bundler installed.

```
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

## How publishing works

Any push to `main` triggers GitHub Pages to rebuild the site automatically. No manual deploy step needed.
