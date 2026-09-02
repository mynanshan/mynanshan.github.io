# GitHub Homepage Guide

A small, dependency-free academic website. The only required files are `index.html` and `style.css`.

## Personalize it first

Search `index.html` for `TODO` and replace:

1. `YOUR_EMAIL` with your email.
2. `YOUR_USERNAME` with your GitHub username.
3. The publication placeholder with exact citations and links.

To add a headshot, create an `assets` folder, save the image as `assets/photo.jpg`, and replace the portrait-placeholder `<div>` using the commented `<img>` line immediately above it.

To add your CV, save it as `assets/cv.pdf` and uncomment the CV link in `index.html`.

## Publish at `YOUR_USERNAME.github.io`

1. Sign in to GitHub and create a **public** repository named exactly `YOUR_USERNAME.github.io`.
2. Upload the contents of this folder to the repository root. `index.html` must be at the top level, not inside another folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After a minute or two, visit `https://YOUR_USERNAME.github.io`.

For later updates, edit or upload the changed file and commit it to `main`; GitHub Pages republishes automatically.

## Optional local preview

You can double-click `index.html`. For a more accurate preview, run this command inside the folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## What belongs on a useful academic homepage

Keep the first screen concise: name, role, institution, two-sentence research identity, email, CV, and GitHub/Scholar links. Below it, show three to five current projects and a complete publication list. Update the site whenever a paper, preprint, talk, award, or position changes; avoid copying your entire CV into the page.
