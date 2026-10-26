# Modern Workshop Website

A responsive, single-page conference site built with HTML, CSS and vanilla JavaScript. No build tools or dependencies are required (Google Fonts and the example hero photograph are fetched online).

## Preview

Open `index.html` in a browser. For a local server, run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Customize

1. Open `content.js` and edit the workshop title, subtitle, date, venue, overview, registration information, agenda, and speakers.
2. Set `registrationUrl` to a real registration URL. Leave it empty until the link is ready.
3. Set each speaker's `photo` to a local path such as `assets/speaker-one.jpg` (create the `assets` folder), or leave it empty to show initials.
4. To use your own hero photo, replace the `url(...)` in `.hero-art` in `styles.css` with `url('assets/banner.jpg')`.
5. Replace the placeholder text and update the logo/branding as needed in `index.html`.

The sample schedule, speaker names, date and location are placeholders. Do not publish them as confirmed event information.

## Publish with GitHub Pages

1. Create a public GitHub repository (for example `workshop-website`).
2. Upload **the files inside** this folder to the repository root (`index.html`, `styles.css`, `script.js`, `content.js`).
3. Commit the files to the `main` branch.
4. Go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Your site will appear at `https://YOUR-USERNAME.github.io/workshop-website/` after deployment.

No npm install or build step is necessary. You can host the site without the external photo/font requests by replacing the image with a local file and using system fonts.
