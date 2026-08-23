# sonukp.in

A scientific professional portfolio built with Astro and designed for GitHub Pages.

## Repository
Use the repository name `sonukp08.github.io`.

## Local development
Install Node.js 22+ and run:

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
```

## GitHub Pages
1. Push this project to the `sonukp08.github.io` repository.
2. Repository → Settings → Pages.
3. Set **Source** to **GitHub Actions**.
4. Push to `main`; the included workflow deploys the site.
5. Keep the custom domain as `sonukp.in`.

## Scientific Notes
Add Markdown files to `src/content/notes/`. Each file becomes its own article automatically.

Example frontmatter:

```yaml
---
title: "My Scientific Note"
description: "A short description."
date: 2026-08-24
category: "Surface Science"
tags: ["BET", "materials"]
readingTime: "6 min read"
featured: false
---
```

The article will appear at `/notes/my-scientific-note/`.

Replace the placeholder professional content and profile links before final launch. Avoid publishing confidential or proprietary information from current industry work.
