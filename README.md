# Zah Industries — website

A responsive, one-page company website built with plain HTML, CSS and JavaScript. No framework, build step, server or paid service is required.

## Preview locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a GitHub repository named `zah-industries` (or `YOUR-USERNAME.github.io`).
2. Upload the contents of this folder to the repository root. Keep `index.html`, `style.css`, `script.js` and `assets/` together.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. GitHub will show the public website address in the Pages section.

## How to replace images
You do not need to edit the code if you keep the same filenames:
- Main logo: `assets/logo.png`
- Browser tab icon: `assets/favicon.png`
- ZahSales image: `assets/zahsales/sales-example.png`
- ZahMedia image: `assets/zahmedia/motodrive-channel.png`

To replace an image, upload your new image with the same filename and overwrite the old one. Commit the change to GitHub; the website will update automatically.

## How to add or change projects
Open `index.html` in a text editor (for example, VS Code or GitHub's web editor). In the `Selected Work` section, duplicate a `<article class="work-item">...</article>` block and change:
- the image path in `src`
- the image description in `alt`
- the category and project title
- the short project description
- the link URL, if needed

Put new images inside `assets/` or the relevant division folder. Use short filenames without spaces, for example `new-project.jpg`.

## How to change text and links
Edit the text directly in `index.html`. Replace the sample email `contact@zahindustries.com` with your real business email. Replace the `href="#"` on the MotoDrive link with the actual public YouTube channel URL.

## Notes
- The company establishment date is shown as August 2026, as supplied.
- The ZahDigital project tile is a placeholder until real project images are available.
- The sample marketplace screenshot and YouTube channel screenshot are used as supplied. Replace them whenever you want.
- Google Fonts are loaded online; system fonts will be used if the visitor is offline.


## Updated visual design
The site now uses a premium dark navy/black technology aesthetic, silver typography, a compact header logo, neon-accent division buttons and smooth hover transitions. The dark-background logo is `assets/logo-dark.png`.
