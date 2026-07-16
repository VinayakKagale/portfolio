# Vinayak Kagale — Portfolio

`index.html` is the site. `resume.pdf` sits next to it and is linked directly — the download
buttons just point to `resume.pdf`, so **updating your résumé is as simple as replacing that file**.

## Deploy on GitHub Pages (free hosting)

1. Go to https://github.com and create a **new repository** (e.g. `portfolio` or `vinayak-kagale.github.io`).
   - Naming it exactly `vinayak-kagale.github.io` puts your site at `https://vinayak-kagale.github.io`.
   - Any other name (e.g. `portfolio`) puts it at `https://vinayak-kagale.github.io/portfolio`.
2. Upload **both** `index.html` and `resume.pdf` to the repo (drag both in at once under
   "Add file" → "Upload files" → Commit changes). They must sit in the same folder.
3. Turn on GitHub Pages: Settings → Pages → Source: "Deploy from a branch" → Branch: `main`,
   folder `/ (root)` → Save.
4. Wait 1–2 minutes, refresh the Pages settings page, and your live URL appears at the top.

## Updating the résumé yourself (no editing needed)

1. Rename your new résumé file to exactly `resume.pdf` (same name as the old one).
2. In your GitHub repo, click on the existing `resume.pdf` → the trash/delete icon → commit
   the deletion (or just go to "Add file → Upload files" and upload the new one — GitHub will
   ask if you want to replace the existing file, say yes).
3. Commit the change.
4. On your live site, hard-refresh the page (Ctrl+Shift+R / Cmd+Shift+R) — browsers cache
   PDFs aggressively, so a normal refresh sometimes still shows the old file for a bit.

That's it — no HTML editing required, ever, for résumé updates.

## Updating other content

All text (About, Skills, Experience, Projects, Education) lives directly in `index.html` as plain
HTML — open it in any text editor (VS Code recommended) and edit the relevant section.
