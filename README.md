# Web Design Portfolio

A Jekyll-powered static site for web design and development projects.

## Quick Start

### Prerequisites
- Ruby 2.5 or higher
- Bundler

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run Jekyll locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and visit `http://localhost:4000`

## Project Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML templates
├── _posts/              # Blog posts (add here)
├── assets/              # CSS, images, and other assets
├── Gemfile              # Ruby dependencies
├── index.md             # Homepage
└── README.md            # This file
```

## Adding Content

### Creating Posts

Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: Your Post Title
date: 2026-04-26
categories: web design
---

Your content here...
```

### Creating Pages

Create new `.md` files in the root directory or subdirectories:

```markdown
---
layout: default
title: Page Title
permalink: /custom-url/
---

Content here...
```

## Deployment

### GitHub Pages

1. Push your changes to the `main` branch
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" and choose `main`
4. Your site will be available at `https://matthewjoelbrooks.github.io/webdes`

## Customization

- Edit `_config.yml` to change site title, author, and settings
- Modify `_layouts/default.html` to change the site structure
- Update `assets/css/style.css` for styling changes
- Change the theme by updating the `theme` value in `_config.yml`

## Learn More

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Markdown Syntax](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## License

MIT License - Feel free to use this for your projects!
