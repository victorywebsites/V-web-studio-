# V-Web Studio website

A responsive multi-page website for V-Web Studio, designed for GitHub Pages. Built with plain HTML, CSS and JavaScript; no build tools, frameworks or package installation required.

## Pages
- `index.html` — Home
- `services.html` — Services
- `portfolio.html` — 12 industry concept mockups
- `about.html` — About the studio
- `packages.html` — Three service tiers
- `contact.html` — WhatsApp-first contact page

## WhatsApp
All WhatsApp links currently point to `https://wa.me/2347074286823`. The number is formatted internationally without `+` or spaces. You can change it by searching all files for `2347074286823`.

## Publish with GitHub Pages
1. Download and unzip the project.
2. Create a new GitHub repository.
3. Upload **the contents of this folder** (not the outer folder) to the repository root. Keep `assets/` and the HTML files together.
4. In the repository, open **Settings → Pages**.
5. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Open the published URL and test every page and WhatsApp link on your phone.

## Important: set your actual site URL for search visibility
Before launch, replace `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY` in `robots.txt` and `sitemap.xml` with your real GitHub Pages username and repository name. Add the canonical URL in each HTML page's `<link rel="canonical" href="">` tag once the final URL is known. For a project site, the URL usually looks like `https://USERNAME.github.io/REPOSITORY/`; for a user/organization site, it may look like `https://USERNAME.github.io/`.

After publishing:
- Check that every page opens and every asset loads over HTTPS.
- Register the site in Google Search Console and submit the sitemap if useful.
- Inspect important URLs for indexing. Discovery and ranking are not guaranteed.
- If you later add a custom domain, update canonical URLs, sitemap, robots.txt and Search Console.
- Confirm your public contact details and package wording before sharing with clients.

## Portfolio transparency
The portfolio cards are illustrative design concepts for 12 industries, not claims of completed client projects. Keep that note visible unless you replace the concepts with genuine work and have permission to show it.

## Notes
- Google Fonts are loaded from Google Fonts; if unavailable, the site uses system fallbacks.
- No external JavaScript library is required.
- Animations respect the visitor's reduced-motion preference.
- This is a static website. It does not include a backend or form processing; enquiries go directly to WhatsApp.
