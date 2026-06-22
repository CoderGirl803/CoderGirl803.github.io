# codergirl803.github.io

A personal GitHub Pages portfolio with:

- A profile-style homepage.
- Header navigation for Projects, Blog, and Achievements.
- Markdown-powered entries in `content/projects`, `content/blog`, and `content/achievements`.
- Ordered content through `content/index.json`.
- Per-entry article styling through the `style` front matter value.

## Add Content

1. Create a Markdown file in the matching folder.
2. Add front matter at the top:

```md
---
title: "My New Project"
summary: "Short description shown on cards."
date: "2026"
order: 1
stack: "HTML, CSS"
style: "deep"
---
```

3. Add the file name to the matching array in `content/index.json`.

Available styles are `deep`, `lab`, and `warm`.
