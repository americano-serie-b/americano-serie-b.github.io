# 🚀 **Chirpy Starter + Obsidian Workflow**

This repository is based on [Chirpy Starter](https://github.com/cotes2020/chirpy-starter), adapted for users who use **Obsidian as a personal knowledge management (PKM) system**. The goal is to turn your notes repository into a professional blog, with automatic deployment and zero friction.

<!-- markdownlint-disable-next-line -->
<div align="center">

  <!-- markdownlint-disable-next-line -->
  # Chirpy Jekyll Theme

  A minimal, responsive, and feature-rich Jekyll theme for technical writing.

  [![CI](https://img.shields.io/github/actions/workflow/status/cotes2020/jekyll-theme-chirpy/ci.yml?logo=github)][ci]&nbsp;
  [![Codacy Badge](https://img.shields.io/codacy/grade/4e556876a3c54d5e8f2d2857c4f43894?logo=codacy)][codacy]&nbsp;
  [![GitHub license](https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy?color=goldenrod)][license]&nbsp;
  [![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy?&logo=RubyGems&logoColor=ghostwhite&label=gem&color=orange)][gem]&nbsp;
  [![Open in Dev Containers](https://img.shields.io/badge/Dev_Containers-Open-deepskyblue?logo=linuxcontainers)][open-container]

  [**Live Demo** →][demo]

  [![Devices Mockup](https://chirpy-img.netlify.app/commons/devices-mockup.png)][demo]

</div>

---

## 🚀 **Get Started**

### 1️⃣ **Create your repository from the template**

1. Click **"Use this template"** at the top of this repository.
2. Name your repository in the format:

```
{your-username}.github.io
```

Example:

```
nonaka.val.github.io
```

---

### 2️⃣ **Enable GitHub Pages**

1. Go to **Settings → Pages** in your repository.
2. Under **Build and deployment**, choose:

```
Source: GitHub Actions
```

✅ This enables automatic publishing whenever you push changes.

---

### 3️⃣ **Configure your blog**

Edit the `_config.yml` file with your information:


```yaml
title: My Notes Blog
tagline: Reflections, Studies, and Learnings
url: "https://{your-username}.github.io"
author:
  name: Your Name
  bio: Explorer of ideas, learnings, and digital solutions
  email: your@email.com
lang: en
```

You can also customize themes, colors, menus, and other settings if desired.

---

### 4️⃣ **Clone the repository locally**

```bash
git clone https://github.com/{your-username}/{your-username}.github.io.git
```

---

### 5️⃣ **Connect Obsidian**

1. Open **Obsidian**.
2. Go to **"Open Folder as Vault"**.
3. Select the `_posts` folder from your cloned repository.

From this point on, any note created in Obsidian inside the `_posts` folder can be published to the blog.

---

### 6️⃣ **Publish your first note**

1. Create a file following the format:

```
YYYY-MM-DD-note-title.md
```

Example:

```
2025-05-27-first-note.md
```

2. Add the following frontmatter at the beginning of the note:

```yaml
---
title: "Note Title"
date: 2025-05-27 12:00:00 +0000
categories: [Notes]
tags: [obsidian, markdown, blog]
---
```

3. After saving, run:

```bash
git add .
git commit -m "Publishing first note"
git push
```

✨ Done! Your note will be automatically published on the blog.

---

## 🗂️ **Recommended Structure**

| Folder     | Description                                   |
| ---------- | --------------------------------------------- |
| `_posts`   | Your public notes (markdown with frontmatter) |
| `_tabs`    | Static pages (About, Contact, Archive, etc.)  |
| `assets`   | Images, files, and media                      |
| `_plugins` | Additional functionalities                    |

---

## 📚 **Resources and Documentation**

* 🐦 [Official Chirpy Theme Guide](https://github.com/cotes2020/jekyll-theme-chirpy/wiki)
* 🔧 [Jekyll Documentation](https://jekyllrb.com/docs/)
* ✍️ [Markdown Guide for Obsidian](https://help.obsidian.md/)

---

## 🤝 **Contributing**

This template is an adaptation designed to integrate the Obsidian workflow with web publishing. Suggestions for improvements, new features, and fixes are always welcome! Open an issue or submit a pull request.

---

## License

This project is published under [MIT License][license].

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[ci]: https://github.com/cotes2020/jekyll-theme-chirpy/actions/workflows/ci.yml?query=event%3Apush+branch%3Amaster
[codacy]: https://app.codacy.com/gh/cotes2020/jekyll-theme-chirpy/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade
[license]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE
[open-container]: https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/cotes2020/jekyll-theme-chirpy
[jekyllrb]: https://jekyllrb.com/
[clipartmax]: https://www.clipartmax.com/middle/m2i8b1m2K9Z5m2K9_ant-clipart-childrens-ant-cute/
[demo]: https://cotes2020.github.io/chirpy-demo/
[wiki]: https://github.com/cotes2020/jekyll-theme-chirpy/wiki
[contribute-guide]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/docs/CONTRIBUTING.md
[contributors]: https://github.com/cotes2020/jekyll-theme-chirpy/graphs/contributors
[lib]: https://github.com/cotes2020/chirpy-static-assets
[vscode]: https://code.visualstudio.com/
[jetbrains]: https://www.jetbrains.com/?from=jekyll-theme-chirpy