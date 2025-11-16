# Hugo Quickstart

This project uses [Hugo](https://gohugo.io/), a fast static site generator. The steps below cover the basics so you can preview and publish the site.

## Prerequisites
- Install the latest **Hugo Extended** release for your platform. Verify with:
  ```bash
  hugo version
  ```
- Optional but useful: install Git to version-control content updates.

## Local Development
1. Start the built-in server:
   ```bash
   hugo server
   ```
2. Open the URL shown in the terminal (default: http://localhost:1313/) to preview changes live.
3. Stop the server with `Ctrl+C` when you are finished.

## Creating Content

Posts are organized in year/month folders and created using archetypes (templates):

**Create a monthly meetup post:**
```bash
hugo new --kind meetup posts/2025/2025-12/2025-12-meetup.md
```

**Create an announcement:**
```bash
hugo new --kind announcement posts/2025/2025-12/2025-12-15-announcement-topic.md
```

**Create a technical article:**
```bash
hugo new --kind technical posts/2025/2025-12/2025-12-15-article-title.md
```

Hugo automatically creates the folder structure and fills in templates with placeholders for you to edit.

For detailed instructions, see **[docs/CONTENT_GUIDE.md](docs/CONTENT_GUIDE.md)**.

## Building for Production
- Create the static site output:
  ```bash
  hugo
  ```
- Hugo writes the compiled site to the `public/` directory. Deploy the contents of `public/` to your hosting provider or static hosting service.

## Customizing the Site
- Global settings (title, theme, params) live in `hugo.toml`.
- Static assets such as images and downloads go in `static/`. Organize them in subdirectories like `static/images/` for easy management.
  - Reference in posts: `![Alt text](/images/photo.jpg)` (note the leading `/`)
- Custom styles and pipeline-ready assets go in `assets/`.
- Layout overrides reside in `layouts/`. Anything placed here takes precedence over the theme defaults.

## Additional Resources

- **[docs/CONTENT_GUIDE.md](docs/CONTENT_GUIDE.md)** - Complete guide for creating and organizing posts
- **[AGENTS.md](AGENTS.md)** - Repository guidelines and conventions
- [Official Hugo documentation](https://gohugo.io/documentation/)
