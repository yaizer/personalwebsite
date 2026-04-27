# Personal Website

A static personal website with sections for hero, accomplishments, education, and contact.

## Local preview

1. Open `index.html` directly in your browser.
2. Or run a local static server from this folder:
   - Python 3: `python3 -m http.server 8000`
   - Visit `http://localhost:8000`

## Deploy to GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

1. Push this repository to GitHub.
2. In GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, choose **Source: GitHub Actions**.
4. Push to `main` (or run the workflow manually from the Actions tab).
5. After the workflow succeeds, your site will be live at:
   - `https://<your-username>.github.io/<repository-name>/`

## Update content

- Main content: `index.html`
- Styling: `styles.css`
- Animation and dynamic year: `script.js`
