# Chloe Chan — personal site

Static personal site built from a CV. Ready to drag-and-drop to GitHub Pages.

## Folder structure

```
deploy/
├── index.html        ← entry point (GitHub Pages needs this at the repo root)
├── assets/
│   └── image1.png    ← your headshot
└── README.md         ← this file
```

## How to deploy on GitHub (drag-and-drop, no terminal)

1. Go to https://github.com/new
2. Repository name: `chloe-chan.github.io` (replace `chloe-chan` with your GitHub username — this makes your site live at `https://<username>.github.io`)
3. Choose **Public**, leave everything else empty, click **Create repository**
4. On the empty repo page, click the link **uploading an existing file** (or **Add file → Upload files**)
5. Open the `deploy/` folder in Finder
6. **Select both `index.html` and the `assets` folder** and drag them into the upload area in the browser
7. Scroll down, click **Commit changes**
8. Go to **Settings → Pages** (left sidebar)
9. Under **Source**, choose **Deploy from a branch**, branch: `main`, folder: `/ (root)`, click **Save**
10. Wait ~1 minute. Your site will be live at `https://<username>.github.io`

## Important: keep the `assets` folder

The HTML references `assets/image1.png`. If you only drag `index.html`, the photo will be missing. Drag both `index.html` and the `assets` folder together.

## After it's live

- Replace the placeholder email/phone/LinkedIn in `index.html` with the real ones, then drag the updated file back in to overwrite.
- Want a custom domain? Buy one (e.g. from Namecheap) and add a CNAME file — see GitHub Pages docs.
