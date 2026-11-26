# CompTIA CySA+ CS0-004 Study Lab

A static, mobile-friendly practice application for GitHub Pages.

## Contents

- `index.html` — the application
- `assets/images/` — images extracted from the uploaded Method 2 PDF and displayed with the related questions

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example, `cysa-plus-study-lab`).
2. Upload **all contents** of this folder to the repository root:
   - `index.html`
   - `assets/` (including the `images/` folder)
   - `README.md`
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the Pages deployment to finish. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Important

- Do not upload only `index.html`; the `assets/images/` directory is required for question images.
- Keep the folder structure unchanged, because image paths are relative.
- This is a static website. No backend, database, or build step is required.
- Practice progress and bookmarks are stored in the browser's `localStorage`. They are local to each browser/device and do not automatically sync between devices.
- The app is not an official CompTIA product. The Method 2 PDF includes answers with different provenance; AI-suggested answers are labelled as unverified in the app.
