# Ecom Alloy

The complete two-page Ecom Alloy website, ready to upload to GitHub or any static website host.

## Website files

- `index.html` — homepage
- `about.html` — About Us page
- `style.css` — main layout and responsive styling
- `refinements.css` — visual refinements and motion styling
- `app.js` — particle logo, funnel tabs, calculator, mobile menu and scroll effects
- `favicon.svg` — Ecom Alloy symbol
- `.nojekyll` — disables Jekyll processing when hosted on GitHub Pages

No build step, package installation, API key or server is required. Fonts load from Google Fonts; fallback fonts are provided if that service is unavailable. The email buttons open the visitor's email app. Instagram buttons open the supplied Instagram profile. There is no form backend or database.

## Recommended: GitHub + Cloudflare Pages

GitHub stores your files. Cloudflare Pages publishes them and updates the website when you update your repository.

1. Extract this ZIP.
2. Create a GitHub repository named `ecom-alloy`.
3. Choose **Add file → Upload files** and upload the contents of this folder. `index.html` must be at the top level of the repository, not inside an extra folder. Commit the files.
4. In Cloudflare, open **Workers & Pages → Create application → Pages → Import an existing Git repository**.
5. Connect the `ecom-alloy` repository.
6. Set the production branch to `main`, framework preset to **None**, build command to `exit 0`, and build output directory to `.` (the repository root).
7. Deploy. Cloudflare supplies a `pages.dev` address for your website.

Official instructions: https://developers.cloudflare.com/pages/framework-guides/deploy-anything/

## Alternative: GitHub Pages

The same files are compatible with GitHub Pages. Review GitHub's Pages usage terms when choosing it for a business website:
https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

1. Upload the files to the top level of a GitHub repository as described above.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then save.
5. When deployment completes, GitHub shows the published address. A project repository normally uses `https://YOUR-USERNAME.github.io/ecom-alloy/`.

All internal links use relative paths so they work under a project address as well as a custom domain.

## Add ecomalloy.com later

After you own the domain, add it using your chosen host's custom-domain settings and follow that host's DNS instructions. No custom domain has been configured in these files. Do not add a `CNAME` file until you own the domain and are connecting it to GitHub Pages.

## Editing

Edit text in `index.html` or `about.html`. Edit colours and layouts in the CSS files. Funnel descriptions and the animated logo are in `app.js`.

The contact email is `khuzaimabinyasir992@gmail.com`.
The Instagram profile is https://www.instagram.com/khuzaima_yasir/.

Keep a backup of this folder. Upload future changes to your connected GitHub repository to trigger the host's deployment process.
