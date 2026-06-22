---
title: "Notes on GitHub Pages"
summary: "A few practical constraints that shape a no-build personal site."
date: "2026-06-01"
order: 3
tags: "Static Sites"
style: "warm"
---

## Static by Default

GitHub Pages can host plain HTML, CSS, JavaScript, and Markdown content. A client-side router keeps navigation smooth without requiring a framework.

## Useful Constraint

Browsers cannot list folder contents directly, so this site uses `content/index.json` as the source of truth for order and visibility.
