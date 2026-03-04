# GitHub Pages setup

This folder is ready to upload to a repository named `YOUR-USERNAME.github.io`.

## Files
- `index.html` — home page
- `publications.html` — full preprints and publications
- `talks.html` — full talks list
- `service.html` — refereeing, teaching, and analytics notes
- `style.css` — shared stylesheet

## Deploy on GitHub Pages
1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`.
6. Wait for the site to publish.

## Enable the visit counter
The home page already contains a GoatCounter-ready script, but it is disabled until you change the placeholder.

1. Create a GoatCounter site.
2. Open `index.html`.
3. Find:
   `https://YOURCODE.goatcounter.com/count`
4. Replace `YOURCODE` with your actual GoatCounter site code.
5. Commit and push again.

This will:
- count pageviews,
- show a visible total-site visit counter on the home page,
- and make country / region data available in GoatCounter analytics.

## Optional public visitor map
If you want a visible map of visitor locations, add a widget service after your site is live.
A practical approach is:
- keep GoatCounter for the clean counter and private analytics,
- add a separate visitor map widget only if you really want public geolocation display.

## Editing content
Because this is plain HTML:
- small edits can be made directly on GitHub in the browser;
- larger edits are easiest if you open the files in any text editor locally.

## Source note
The content was adapted from the previous IBS homepage sections:
- About
- Research
- Activities
