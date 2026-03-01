+++
title = "Getting Started"
tags = ["hugo", "setup"]
+++

## Prerequisites

- [Hugo Extended](https://gohugo.io/getting-started/installing/) (v0.128+)
- [Go](https://go.dev/dl/) (for Hugo modules)
- [Git](https://git-scm.com/)

## Local Development

```bash
hugo server -D
```

Open `http://localhost:1313/evergreen/` in your browser.

## Creating Content

```bash
# New note
hugo new notes/my-note.md

# New tech doc
hugo new tech/my-doc.md
```

## Project Structure

```
content/
├── _index.md          # Homepage
├── about.md           # About page
├── notes/             # Notes & journal
│   ├── _index.md
│   └── *.md
└── tech/              # Tech docs
    ├── _index.md
    └── *.md
```
