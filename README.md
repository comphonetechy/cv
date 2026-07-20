# Justine John C. Solas — Portfolio

Personal portfolio site for [Justine John C. Solas](https://github.com/comphonetechy), Full-Stack Developer.

**Live site:** [comphonetechy.github.io/cv](https://comphonetechy.github.io/cv/)

## Structure

```
cv/
├── index.html          # Main portfolio page
├── css/
│   └── style.css       # All styles (no build step)
├── js/
│   └── main.js         # Nav toggle, scroll reveal
├── assets/
│   └── favicon.svg     # Site favicon
└── README.md
```

## Local Preview

Open `index.html` in a browser, or serve locally:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Deploy to GitHub Pages

1. **Push this repo** to `https://github.com/comphonetechy/cv`

   ```bash
   git add .
   git commit -m "Add portfolio site"
   git push origin main
   ```

2. **Enable GitHub Pages** in the repo settings:
   - Go to **Settings → Pages**
   - Under **Source**, select **Deploy from a branch**
   - Branch: `main` / folder: `/ (root)`
   - Click **Save**

3. **Wait ~1–2 minutes** for the build. Your site will be live at:
   `https://comphonetechy.github.io/cv/`

## Custom Domain (Optional)

To use a custom domain instead of `github.io/cv`:

1. Add a `CNAME` file at the repo root with your domain
2. Configure DNS with your registrar (A records or CNAME to GitHub Pages)
3. Enable HTTPS in repo **Settings → Pages**

## Tech Stack

- Static HTML5 + CSS3 + vanilla JavaScript
- No build tools or dependencies required
- Mobile responsive with smooth scroll navigation
- SEO and Open Graph meta tags included
