# 📝 Dynamic Blogging Platform

## Overview
A fully featured blog website with categories, tags, search, sidebar widgets,
newsletter signup, and pagination. Built as a standalone HTML/CSS/JS site — also
includes complete WordPress deployment instructions.

## Features
- Sticky navigation with search bar
- Hero banner with email subscribe form
- Category tab filter system (8 categories)
- Featured post hero card
- 6-post grid layout with thumbnails
- Sidebar: Popular Posts, Categories, Tag Cloud, Newsletter
- Pagination component
- Responsive footer with 4-column grid
- Mobile responsive

## Technologies Used
| Tool | Purpose |
|------|---------|
| HTML5 | Structure |
| CSS3 | Grid, Flexbox, animations |
| JavaScript (Vanilla) | Tab switching, pagination |
| WordPress | CMS backend (deployment) |
| RankMath / Yoast SEO | SEO optimization (WordPress) |

## Project Structure
```
07_blogging_platform/
│
├── index.html     ← Complete standalone blog (open in browser)
└── README.md
```

## How to Run

### Standalone
```
Double-click index.html to open in any browser.
```

### WordPress Deployment
1. Install WordPress + **Elementor** (free) plugin
2. Install a blogging theme (e.g., Astra, OceanWP, GeneratePress)
3. Create Posts → Add categories and tags per article
4. Install **RankMath SEO** plugin:
   - Enable Schema markup for BlogPosting
   - Set focus keywords for each post
   - Enable XML sitemap
5. Install **MailChimp for WordPress** for the newsletter form
6. Customize sidebar with **Widget** settings:
   - Add Popular Posts widget (Jetpack or custom)
   - Add Category widget
   - Add Tag Cloud widget
7. Add search functionality: WordPress has built-in search widget

## SEO Implemented
- Meta title, description, keywords
- Semantic heading hierarchy (h1 → h2 → h3)
- Category structure for URL organization
- Tag cloud for topical relevance
- Newsletter for audience building
