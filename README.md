# Personal Blog

A minimalist Jekyll blog inspired by [Paul Graham's website](https://paulgraham.com/).

## Setup

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`

## Site Navigation

The site includes a left sidebar with:
- **Profile Section** - Your photo, name, Twitter, and GitHub
- **Navigation Links**:
  - Home - Introduction and recent essays
  - Blogs - All blog posts
  - Books - Book recommendations
  - About Me - Personal information

## Adding Your Profile Photo

Place your profile photo at `assets/images/profile.jpg`. The photo should be square (300x300px or larger recommended). If no photo is present, the layout will display your name and social links without the image.

## Adding Essays

Create new essays in the `_essays/` directory:

```markdown
---
layout: essay
title: Your Essay Title
date: YYYY-MM-DD
---

Your content here...
```

Essays will automatically appear on the homepage and blogs page in reverse chronological order.

## Editing Pages

To customize the content:
- **Homepage introduction**: Edit `index.html`
- **Books list**: Edit `books.html`
- **About page**: Edit `about.html`
- **Resume**: Edit `resume.html`

All pages use simple HTML/Markdown. Just edit the text between the tags.

## Customization

- Edit `_config.yml` to change your name, email, and description
- Modify `assets/css/style.css` to adjust styling
- Update `_layouts/` for layout changes

## Structure

```
├── _essays/          # Your essays go here
├── _layouts/         # Page layouts
│   ├── default.html  # Base layout with sidebar
│   └── essay.html    # Essay layout
├── assets/css/       # Stylesheets
├── index.html        # Homepage with introduction
├── blogs.html        # All blog posts
├── books.html        # Book recommendations
├── about.html        # About me page
├── resume.html       # Resume/CV
└── _config.yml       # Site configuration
```

Keep it simple. Focus on writing.
