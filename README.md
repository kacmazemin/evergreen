# MyConf

Personal knowledge wiki built with [Hugo](https://gohugo.io/) and the [Relearn](https://mcshelby.github.io/hugo-theme-relearn/) theme.

## Quick Start

```bash
# Start local dev server (with drafts)
hugo server -D
```

Open [http://localhost:1313](http://localhost:1313).

## Creating Content

```bash
# New journal entry
hugo new notes/2026-03-01-my-finding.md

# New tech doc
hugo new tech/architecture-overview.md
```

## Deployment

Push to `main` branch — GitHub Actions will build and deploy to GitHub Pages automatically.

```bash
git add . && git commit -m "Add new notes" && git push
```

## Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.112+)
- [Go](https://go.dev/dl/) (for Hugo modules)
- [Git](https://git-scm.com/)
