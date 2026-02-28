# My Personal Website

A clean, single-file personal site with portfolio, blog, resume, and links sections.

## Quick Start

1. Open `index.html` in your browser to preview
2. Search for `EDIT:` comments in the HTML to find everything you should customize
3. Replace placeholder text with your own content

## How to Edit

Everything is in **one file** (`index.html`) — no build tools needed. Open it in any text editor (VS Code, Sublime, Notepad, etc.).

### Key things to customize:
- **Your name & bio** — in the Hero section near the top
- **Projects** — copy/paste a `project-card` div to add more
- **Blog posts** — copy/paste a `blog-entry` div to add more
- **Resume** — update job titles, companies, dates, and skills
- **Links** — update URLs and add/remove `link-card` blocks
- **Photo** — replace the placeholder div with an `<img>` tag
- **Colors** — change the CSS variables at the top (`:root` section)

## Deploy to GitHub Pages (Free)

### First-time setup:
```bash
# 1. Create a new repo on github.com named "yourusername.github.io"

# 2. Initialize and push:
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

Your site will be live at `https://yourusername.github.io` within a minute!

### Every time you make changes:
```bash
git add .
git commit -m "Update site"
git push
```

That's it — two commands to deploy.

## Alternative: Deploy with Netlify

```bash
# Install once:
npm install -g netlify-cli

# Deploy:
netlify deploy --prod --dir .
```

## File Structure

```
├── index.html    ← Your entire website (edit this!)
└── README.md     ← You're reading this
```

Add images by placing them in the same folder and referencing them in the HTML.
