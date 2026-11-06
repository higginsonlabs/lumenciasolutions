# Lumencia Solutions – static site

Pages: `index.html`, `service-tiers.html`, `how-it-works.html`, shared styles in `style.css`.

## Host it free on GitHub Pages
1. Create a free account at github.com and click **New repository** (name it e.g. `lumencia`, set it to Public).
2. Click **uploading an existing file**, drag in everything in this folder (the three .html files and style.css), then **Commit changes**.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, and Save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/lumencia/`.

Custom domain: Settings → Pages → Custom domain, then add the DNS records GitHub shows you at your domain provider.

## Two things to do before you cancel Wix
- **Contact form:** it currently opens an email to lumenciasolutions@outlook.com. For a proper form, create a free form at formspree.io, then replace `YOUR_FORM_ID` in `index.html` (the form `action` URL) with your form ID.
- **Images:** the images still load from Wix's servers. Download each image from your Wix media manager, put them in an `images/` folder here, and update the image links at the top of `style.css` and in the footer `<img>` tags. Otherwise they may disappear after you cancel Wix.
