# Shengze Ding's Academic Website

This is my personal academic website built with Jekyll and the AcademicPages theme.

## Features

- 📱 **Responsive Design**: Works perfectly on all devices
- 🌙 **Dark Mode Support**: Automatic dark mode based on system preferences
- 📚 **Academic Focus**: Clean, professional layout for academic content
- 🔍 **SEO Optimized**: Built-in SEO features
- 📝 **Blog Support**: Easy to add blog posts
- 🎨 **Customizable**: Easy to customize colors and layout

## Local Development

### Prerequisites

- Ruby 2.7 or higher
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

## Content Structure

- `index.md` - Home page
- `_pages/` - Additional pages (CV, Publications, Projects)
- `_posts/` - Blog posts (if needed)
- `assets/` - Images and other assets

## Customization

### Update Personal Information

Edit `_config.yml` to update:
- Site title and description
- Author information
- Social media links

### Add New Pages

Create a new markdown file in `_pages/` directory:

```markdown
---
layout: single
author_profile: true
title: "Page Title"
permalink: /page-url/
---

Your content here...
```

### Add Blog Posts

Create a new markdown file in `_posts/` directory with the naming convention: `YYYY-MM-DD-title.md`

## Deployment

This site is automatically deployed to GitHub Pages when you push to the main branch.

## License

MIT License - See LICENSE file for details

## Contact

- Email: shengzeding@sjtu.edu.cn / sding@nd.edu
- LinkedIn: [shengze-ding](https://www.linkedin.com/in/shengze-ding)
- GitHub: [shengzeding](https://github.com/shengzeding)

