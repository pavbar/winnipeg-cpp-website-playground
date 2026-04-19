# Repository Index

This file is the canonical source for repository structure and navigation.

## Top-level map

- `content/` - Markdown source for meetup posts, announcements, and technical articles.
- `archetypes/` - Hugo archetypes used to scaffold new content.
- `static/` - Files copied directly into the published site, such as images and downloads.
- `layouts/` - Local Hugo layout overrides that take precedence over the theme.
- `themes/PaperMod/` - Git submodule for the PaperMod Hugo theme.
- `docs/` - Contributor-facing documentation for creating and organizing content.
- `.github/workflows/` - CI and deployment workflows for build verification and Pages deploys.
- `public/` - Generated build output. Do not edit by hand.

## Key entrypoints

- [`README.md`](README.md) - Human-oriented overview, quick start, and key commands.
- [`AGENTS.md`](AGENTS.md) - Repo-scoped operating rules for contributors and agents.
- [`docs/CONTENT_GUIDE.md`](docs/CONTENT_GUIDE.md) - Detailed content authoring workflow.
- [`hugo.toml`](hugo.toml) - Hugo configuration, site metadata, menus, and timezone.
- [`layouts/_default/rss.xml`](layouts/_default/rss.xml) - Local RSS override for the site.
- [`archetypes/meetup.md`](archetypes/meetup.md) - Archetype for monthly meetup announcements.

## Navigation notes

`README.md` and `AGENTS.md` should stay shorter than this file and link back here for structure.

## Boundaries

Do not use this file for operating policy, roadmap items, or chronological history.
