---
title: "Welcome to the FinEvals blog"
description: "Why we are writing about AI evaluation evidence, and what you can expect to find here."
author: "FinEvals.ai"
---

This is a placeholder post so the blog has something to render. Replace or
delete it — the file lives at `_posts/2026-08-21-welcome-to-the-finevals-blog.md`.

## What we plan to write about

Most teams deploying AI in financial services end up holding two very different
kinds of evidence. There is the evidence that the system works, produced by the
engineering team. And there is the evidence a second-line validator, internal
audit or a regulator will actually accept. They are rarely the same thing.

We expect to write about:

- What separates an eval that convinces an engineer from one that convinces a validator.
- Where deterministic grading is possible, and where it genuinely is not.
- How to report the limits of a test honestly, without undermining the result.
- What the EU AI Act and comparable regimes can and cannot be evidenced by behavioural testing.

## How to add a post

Drop a Markdown file into `_posts/` named `YYYY-MM-DD-a-short-slug.md`, with
front matter at the top:

```yaml
---
title: "Your title here"
description: "One or two sentences, used on the blog index."
author: "Your name"
---
```

Everything below the front matter is ordinary Markdown. Commit it to `main` and
GitHub Pages rebuilds the site automatically — there is no build step to run.
