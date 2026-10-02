# Portfolio Creation

This project is a responsive personal portfolio website themed around public service, leadership, and community impact. It includes the required sections for a personal statement, skills showcase, and projects portfolio, and uses Erie County District Attorney's Office information as a contextual design reference.

## Run locally

Open the project folder in a browser, or use a simple local server from the workspace:

```bash
cd /workspaces/Portfolio-Creation
python3 -m http.server 8000
```

Then visit http://localhost:8000 in your browser.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the site to
https://dr-touse.github.io/Portfolio-Creation/ whenever changes are pushed to
`main`. In the repository settings, set **Pages → Build and deployment → Source**
to **GitHub Actions** if it is not already selected.

## Files

- `index.html` — page structure and content
- `styles.css` — styling and responsive layout
- `script.js` — simple footer year script
