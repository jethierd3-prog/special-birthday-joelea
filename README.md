# Joelea’s Birthday Garden ✿

A responsive birthday surprise website for Joelea, featuring a cinematic purple floral intro, a birthday letter, Bible verses, hidden flower wishes, and a tiny interactive garden.

## Preview locally

This is a plain static website—no build tools, server, or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

Google Fonts are loaded from Google Fonts when an internet connection is available; the site still uses fallback fonts if they are unavailable.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `joelea-birthday-garden`).
2. Extract this ZIP file on your computer.
3. Upload the **contents** of this folder to the repository's top level. Make sure `index.html` is at the top level and keep the `css/`, `js/`, and `music/` folders intact. Do not upload only the ZIP file.
4. On GitHub, open the repository and go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the deployment to finish. GitHub will show the published site URL in the Pages section.

If you use a different branch name, select that branch instead. GitHub Pages may take a few minutes to publish the first time.

## Optional: publish with Render

Create a **Static Site** connected to this repository, then use:
- Branch: `main`
- Root Directory: leave blank
- Build Command: `echo "No build needed"`
- Publish Directory: `.`

## Project files

- `index.html` — page content and birthday message
- `css/style.css` — layout, colors, responsive styles, and intro animation
- `js/main.js` — interactive behaviors
- `music/README.txt` — optional music instructions
- `DEPLOY-STEPS.txt` — quick deployment checklist

## Personalize

Edit the birthday text and content in `index.html`. Keep the linked file paths as they are unless you also move the files. To add music, use only an audio file you own or have permission to use, then add your own audio controls to the page.

This project is a static site and does not require Flask, `requirements.txt`, `Procfile`, npm, or a build step.
