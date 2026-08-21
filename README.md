# finevals.ai

Marketing site for FinEvals.ai, served by GitHub Pages from `main` at the repo
root (see `CNAME`).

## Structure

| Path | What it is |
| --- | --- |
| `index.html` | The landing page. No Jekyll front matter, so it is copied through verbatim. |
| `blog/index.html` | Blog listing page. |
| `_posts/` | Blog posts, one Markdown file each. |
| `_layouts/` | Shared page shell (`default.html`) and post template (`post.html`). |
| `assets/css/style.css` | Vendor template stylesheet — avoid editing. |
| `assets/css/finevals.css` | Our overrides on top of the template. |
| `_config.yml` | Jekyll configuration. |

## Adding a blog post

Create a file in `_posts/` named `YYYY-MM-DD-a-short-slug.md`:

```markdown
---
title: "Your title here"
description: "One or two sentences, shown on the blog index."
author: "Your name"
---

Your post, in ordinary Markdown.
```

Commit it to `main`. GitHub Pages rebuilds automatically — there is no build
step to run and no CI workflow to configure. The post appears at
`/blog/a-short-slug/` and is listed newest-first on `/blog/`.

Posts dated in the future are not published until that date. To draft without
publishing, put the file in a `_drafts/` folder instead.

## Previewing locally

Optional — see `Gemfile`.

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
