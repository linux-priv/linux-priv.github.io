# Linux-Priv Website

> Official website for the Linux-Priv OS distribution.  
> Built with [Hugo](https://gohugo.io/) · Hosted on GitHub Pages

## 🌐 Live Site

**https://linux-priv.github.io**

---

## 🚀 Local Development

### Prerequisites
- [Hugo](https://gohugo.io/installation/) (extended version recommended)
- Git

### Run locally

```bash
git clone https://github.com/linux-priv/linux-priv.github.io
cd linux-priv.github.io
hugo server -D
```

Then open [http://localhost:1313](http://localhost:1313)

---

## 📁 Project Structure

```
linux-priv/
├── content/
│   ├── _index.md          # Homepage
│   ├── download/          # Download page
│   ├── docs/              # Documentation
│   └── blog/              # News & announcements
├── themes/
│   └── linux-priv-theme/  # Custom theme
│       ├── layouts/       # HTML templates
│       └── static/        # CSS, JS, images
├── .github/
│   └── workflows/
│       └── deploy.yml     # Auto-deploy to GitHub Pages
└── hugo.toml              # Site configuration
```

---

## ✏️ Adding Content

### New blog post
```bash
hugo new blog/my-post-title.md
```

### New docs page
```bash
hugo new docs/my-topic.md
```

Each new file gets a front matter header:
```yaml
---
title: "My Title"
date: 2026-04-03
draft: false
---
```

Set `draft: false` (or remove the line) to publish.

---

## 🔧 Configuration

Edit `hugo.toml` to update:
- Site title, description
- Version number
- GitHub URL
- Download URL

---

## 🤝 Contributing

1. Fork this repo
2. Create a branch: `git checkout -b fix/my-fix`
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

GPL-3.0 — see [LICENSE](LICENSE)
