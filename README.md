# Winnipeg C++ Developers

This repository contains the Hugo source for the Winnipeg C++ Developers website, including
meetup announcements, technical posts, and supporting site configuration.

GitHub org: [github.com/winnipeg-cpp](https://github.com/winnipeg-cpp)
Live site: [winnipeg-cpp.github.io/website](https://winnipeg-cpp.github.io/website/)

## Quick Start

Prerequisites:

- [Hugo Extended](https://gohugo.io/installation/)
- Git

From the repository root:

```bash
git submodule update --init --recursive
hugo server -D
```

Open `http://localhost:1313/` to preview the site locally.

## Key Commands

- `hugo server -D` - Preview the site locally with drafts enabled.
- `hugo server -D --buildFuture` - Preview drafts and future-dated posts.
- `hugo` - Build the production site into `public/`.
- `hugo --gc --minify` - Run a clean, minified production build.

## Current Scope

The site currently covers:

- Monthly meetup announcements
- Community announcements
- Technical articles and tutorials
- Shared resources for local C++ developers

## Layout Summary

Key paths:

- `content/` - Markdown content
- `archetypes/` - Post templates
- `layouts/` - Local Hugo overrides
- `themes/PaperMod/` - Theme submodule
- `docs/` - Contributor documentation

See [INDEX.md](INDEX.md) for the canonical repository map.

## Docs

- [docs/CONTENT_GUIDE.md](docs/CONTENT_GUIDE.md) - Detailed content authoring workflow
- [AGENTS.md](AGENTS.md) - Repo-specific operating guidelines
- [INDEX.md](INDEX.md) - Canonical repository structure map
