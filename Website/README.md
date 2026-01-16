# Personal website (GitHub Pages)

This repo is a simple static site (HTML/CSS) intended for GitHub Pages.

Note: This is not a Node/Next.js project. If GitHub Actions is failing with "Unable to determine package manager", remove any Next.js Pages workflow and use the static deploy workflow in `.github/workflows/deploy-pages.yml`.

## Quick start (local)

Open `index.html` in a browser.

## Add your CV PDF

1. Put your CV at:

   `assets/cv/Tian_Wang_CV.pdf`

2. The homepage links to it from the **CV** section.

## Add a profile photo

1. Put your headshot at:

   `assets/img/profile.jpg`

2. The header will display it automatically.

## Publish with GitHub Pages

### Option A: User/Org site (recommended)

1. Create a repo named **`<your-github-username>.github.io`**.
2. Put these files in the repo root.
3. On GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
4. Your site will be at: `https://<your-github-username>.github.io/`

### Option B: Project site

1. Create a repo with any name (e.g., `website`).
2. On GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
3. Your site will be at: `https://<your-github-username>.github.io/<repo-name>/`

## Customize

Edit `index.html` to update:
- contact info (email, scholar, github)
- publications and projects
- tagline and about text

Edit `assets/styles.css` to adjust colors and layout.
