---
title: Getting Started
description: This template allows you to create a personal blog or a public notep site, with automatic publication via Github Pages and local edition using Obsidian.
author: cotes
date: 2019-08-09 20:55:00 +0800
categories:
  - Blogging
  - Tutorial
tags:
  - getting
  - started
pin: true
media_subpath: /posts/20180809
---
# 📘 Publication Workflow — Obsidian → Blog

## 🏗️ Structure

- `_posts/` → Folder where you create and edit your public notes.
- `_tabs/` → Fixed pages (About, Contact, Archive).
- `assets/` → Images and static files to use in notes.
- `_config.yml` → File with blog settings (title, author, description).


## Writing a Post

- Shortcut - `Ctrl + n` Creates a new note.
    - Avoid using spaces, as shown in the example notes. The title and other post values will be set in the frontmatter properties.
- How to link internal notes:

## Calendar and Daily Notes

- Shortcut `Ctrl + Shift + D` to access or create a daily note.

## 🔄 Publishing

When finished:

```bash
git add .
git commit -m "Add new note"
git push
```

---

## 💎 References

- [Chirpy Theme Official Documentation](https://github.com/cotes2020/jekyll-theme-chirpy/wiki)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
