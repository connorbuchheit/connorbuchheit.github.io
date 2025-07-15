# connorbuchheit.github.io

Personal website and blog built with Jekyll using the Minima theme.

## Features

- ✅ **Jekyll-based** - Easy to maintain and update
- ✅ **Minima Theme** - Clean, professional design
- ✅ **Blog System** - Write posts in Markdown
- ✅ **Responsive Design** - Works on all devices
- ✅ **SEO Optimized** - Built-in SEO features
- ✅ **GitHub Pages Ready** - Deploys automatically

## Structure

```
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog posts (Markdown files)
├── index.md             # Homepage
├── about.md             # About page
├── blog.md              # Blog listing page
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Getting Started

### Prerequisites

- Ruby (version 2.5.0 or higher)
- RubyGems
- GCC and Make

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View your site:**
   Open [http://localhost:4000](http://localhost:4000) in your browser.

### Adding Blog Posts

1. Create a new file in the `_posts/` directory
2. Use the format: `YYYY-MM-DD-title.md`
3. Add front matter at the top:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
categories: [category]
tags: [tag1, tag2]
---

Your content here...
```

### Customization

- **Site settings**: Edit `_config.yml`
- **Theme customization**: Override theme files in `_layouts/`, `_includes/`, `_sass/`
- **Styling**: Modify `assets/css/style.scss`

## Deployment

This site is configured for GitHub Pages. Simply push changes to the main branch and GitHub will automatically build and deploy your site.

## License

This project is open source and available under the [MIT License](LICENSE). 
