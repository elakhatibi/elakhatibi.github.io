# Elahe Khatibi — Personal Research Website

A zero-build, responsive academic + industry portfolio website. It is designed to work directly on GitHub Pages, Netlify, or Cloudflare Pages.

## Files

- `index.html` — all website content and metadata
- `styles.css` — responsive design, light/dark theme, animations
- `script.js` — theme toggle, mobile navigation, reveal effects
- `assets/Elahe_Khatibi_CV.pdf` — CV linked from the navigation

## Preview locally

The website is plain HTML/CSS/JavaScript. You can double-click `index.html`, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish free with GitHub Pages

1. Create a GitHub repository named `YOUR-USERNAME.github.io` (for the cleanest URL) or any repository name.
2. Upload everything in this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then **Save**.
6. GitHub will publish the site at:
   - `https://YOUR-USERNAME.github.io/` if the repo is named `YOUR-USERNAME.github.io`, or
   - `https://YOUR-USERNAME.github.io/REPO-NAME/` for a project repository.

For your current GitHub username, the cleanest repository name would be:

`elakhatibi.github.io`

and the resulting website would be:

`https://elakhatibi.github.io/`

## Alternative free hosting

### Netlify
Drag this entire folder into Netlify's deploy interface. No build command is required.

### Cloudflare Pages
Connect the GitHub repository and use no build command; use the repository root as the output directory.

## Easy edits

Search in `index.html` for section headings such as `FEATURED WORK`, `EXPERIENCE`, or `PUBLICATIONS` and edit the text directly.

### Add a professional photo later
If you want a headshot, add it to `assets/` and replace the current research-orbit hero visual. A square or 4:5 portrait works best.

## Notes

The website intentionally does not publish a phone number. It uses your UCI email plus LinkedIn, GitHub, Google Scholar, and DBLP.
