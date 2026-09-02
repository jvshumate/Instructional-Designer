# James Shumate — Instructional Design Portfolio

A single-page portfolio site. No build step, no frameworks: one `index.html`, an `assets` folder, done.

## Deploy to GitHub Pages (about 10 minutes)

1. **Create the repository.** Sign in at github.com → **New repository**. Name it `portfolio` (or `james-shumate-portfolio`). Leave it Public. Don't add a README (this folder already has one). Click **Create repository**.

2. **Upload the files.** On the empty-repo page, click **uploading an existing file**. Drag in `index.html`, `README.md`, and the whole `assets` folder (drag the folder itself; GitHub keeps the structure). Commit with the message "Initial portfolio".

3. **Turn on Pages.** Repository → **Settings** → **Pages** (left sidebar). Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**. Save.

4. **Wait about a minute**, then refresh the Pages settings page. The live URL appears at the top:
   `https://<your-username>.github.io/portfolio/`

5. **Share the RORO slides publicly.** In Google Slides: Share → General access → *Anyone with the link* → Viewer. Otherwise the embed on the site shows a permissions error.

To make the URL shorter (`https://<your-username>.github.io/` with nothing after it), name the repo exactly `<your-username>.github.io` in step 1.

## Updating the site

Edit `index.html` on GitHub (open the file → pencil icon → commit). Pages redeploys in about a minute.

- **Add a work sample:** in the *WORK SAMPLES* section, copy one `<article class="sample frame">…</article>` block, paste it above the `<div class="more">` box, and change the screen number, title, image path, and text. Put the new image in `assets/images/`.
- **Add a headshot:** save it as `assets/images/headshot.jpg` and uncomment the `<img class="portrait">` line in the *ABOUT* section.
- **Replace the resume:** upload a new PDF with the same name, `assets/James_Shumate_Resume.pdf`.

## What's inside

```
index.html                  the whole site (HTML + CSS)
assets/James_Shumate_Resume.pdf
assets/images/              work sample screenshots
```

The site respects dark mode and reduced-motion settings, prints cleanly, and includes a skip link and visible keyboard focus.
