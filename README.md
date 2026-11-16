# Career e-portfolio

A static site with no dependencies or build step.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` from this folder and visit http://localhost:8000.

## Deploy to GitHub Pages
1. Create a public GitHub repository named `YOUR-USERNAME.github.io` (replace with your actual username), or use an ordinary repository name for a project site.
2. Upload the files in this folder directly to the repository root (not inside an additional portfolio folder).
3. Open repository Settings > Pages. Under Build and deployment choose Deploy from a branch, then main and /(root), and save.
4. Once GitHub finishes deployment, open the published address displayed in Pages settings.

## Personalize before publishing
- Verify the name, university email, academic details and project descriptions in `index.html` and `resume.html`.
- Add your actual GitHub/LinkedIn links and project repository links when available.
- To use your existing CV PDF, place it in `assets/resume.pdf` and change the resume button's href in index.html to `assets/resume.pdf`.
- Avoid publishing private IP addresses, credentials, network diagrams with sensitive details, or confidential thesis material.
- Edit colors and typography at the top of `style.css`.
