---
title: "Markdown Portfolio CMS"
summary: "A GitHub Pages portfolio that loads projects, posts, and achievements from Markdown files."
date: "2026"
order: 1
stack: "HTML, CSS, JavaScript"
style: "deep"
---

## Overview

This site uses a tiny client-side content system. Add a Markdown file to the right folder, register it in `content/index.json`, and it appears in the correct order.

## Highlights

- No build step required for GitHub Pages.
- Each entry can choose its own article style with front matter.
- The homepage automatically counts and previews content.

## How to Update

Create files inside `content/projects`, `content/blog`, or `content/achievements`, then add the file name to the matching list in `content/index.json`.
