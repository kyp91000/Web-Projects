# 🌐 Business Portfolio Website

## Overview
A fully responsive, SEO-optimized professional portfolio website for a Data Analyst
and Web Developer. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks
or dependencies required.

## Features
- Fixed navigation bar with smooth scroll & active link highlighting
- Hero section with professional headline, stats, and CTA buttons
- About section with skill tags
- Services section (6 cards with hover effects)
- Portfolio section (6 project cards with category tags)
- Client Testimonials section
- Contact form with validation and success message
- Mobile-responsive design
- SEO meta tags (title, description, keywords)

## Technologies Used
| Tool | Purpose |
|------|---------|
| HTML5 | Structure & semantic markup |
| CSS3 | Styling, Grid, Flexbox, animations |
| JavaScript (Vanilla) | Nav highlight, form validation |
| Elementor (WordPress) | Drag-and-drop page builder (for WP version) |

## Project Structure
```
06_business_portfolio/
│
├── index.html     ← Complete standalone website (open in browser)
└── README.md
```

## How to Run

### Standalone (No server needed)
```
Just double-click index.html to open in any browser.
```

### Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main
# Then enable GitHub Pages in repository Settings → Pages
```

## WordPress Deployment Instructions
1. Install WordPress on your hosting (cPanel → Softaculous)
2. Install **Elementor** plugin (free version)
3. Create a new page → Edit with Elementor
4. Recreate each section using Elementor widgets:
   - Hero: Full-width section + Heading + Button widgets
   - Services: Icon Box widgets in 3-column grid
   - Portfolio: Image Box widgets
   - Contact: WPForms or Contact Form 7 plugin
5. Install **RankMath** or **Yoast SEO** plugin for SEO optimization
6. Set page as Homepage in Settings → Reading

## SEO Checklist (Implemented)
- Meta title and description tags
- Semantic HTML (h1, h2, section, nav, footer)
- Mobile-responsive viewport meta
- Fast-loading (no external dependencies)
- Descriptive alt-ready image placeholders
