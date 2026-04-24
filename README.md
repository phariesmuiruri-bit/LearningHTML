# Dining Table Setup — Learning Journal

This repository contains a small learning project: a single-page website that demonstrates HTML structure, CSS styling, and basic Git/GitHub workflows.

## What I learned
- HTML structure and semantic sections (`nav`, `section`, `header`) and proper element placement.
- Building a responsive navbar with a logo and right-aligned links using Flexbox.
- Styling with CSS: color scheme, spacing, typography, hover effects, shadows, and visual hierarchy.
- Layout patterns: container max-width, two-column feature layout using CSS Grid, and responsive image handling.
- Organizing content: About, Services, Contact, and Home (hero) sections with IDs for in-page navigation.
- Git basics: `git init`, `git add`, `git commit`, `git remote add`, and `git push` to upload to GitHub.

## Files
- `Home.html` — Main HTML file containing the site markup and embedded CSS.
- `README.md` — This documentation.

## How to view locally
1. Open `Home.html` in your browser (double-click or use Live Server in VS Code).
2. Or serve locally with a simple server (Python example):

```bash
# from the project folder
python -m http.server 8000
# then open http://localhost:8000/Home.html
```

## Git commands I used
```bash
git init
git add .
git commit -m "Initial commit: Dining table setup website with navbar and sections"
git remote add origin https://github.com/phariesmuiruri-bit/LearningHTML.git
git push -u origin main
```

## GitHub Pages (optional)
To publish the site via GitHub Pages:
1. Go to the repository on GitHub > Settings > Pages.
2. Choose branch `main` and root (`/`) as the source, then Save.
3. GitHub will provide a URL like `https://<username>.github.io/LearningHTML`.

## Next improvements to document
- Add a small logo image file instead of the emoji and update `nav .logo` to use it.
- Move CSS into a separate `styles.css` and practice linking external stylesheets.
- Add a small contact form and learn basic form handling.
- Add automated tests or CI (GitHub Actions) for practice.

---
If you want, I can: add a `LICENSE`, enable GitHub Pages for you, or split CSS into a separate file now. Which would you like next?