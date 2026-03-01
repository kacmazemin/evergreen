---
title: "Getting Started"
date: 2026-03-01
tags: ["hugo", "setup"]
---

## Prerequisites

- [Hugo Extended](https://gohugo.io/getting-started/installing/) (v0.100+)
- [Go](https://go.dev/dl/) (for Hugo modules)
- [Git](https://git-scm.com/)

## Local Development

```bash
hugo server -D
```

Open `http://localhost:1313/evergreen/` in your browser.

## Creating Content

```bash
# New post
hugo new posts/my-post.md
```

## Project Structure

```
content/
├── _index.md          # Homepage
├── about/
│   └── index.md       # About page
└── posts/             # Blog posts
    └── *.md
```
