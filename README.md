# Stray Bullet — GitHub Pages Portfolio

A responsive, static **product & team portfolio** for Stray Bullet.

The site is intentionally a **project showcase**, not a shop, SaaS application, account portal or payment form. Account and commerce functions stay on the official Stray Bullet website. GitHub Pages' terms restrict using Pages to run online businesses, e-commerce sites or commercial SaaS sites.

## Included

```text
stray-bullet-portfolio-site/
├── index.html      # all website content and sections
├── styles.css      # responsive styles, dark and light themes
├── script.js       # mobile navigation, tabs and theme switcher
├── 404.html        # fallback page
├── .nojekyll       # publish files as-is
├── assets/
│   ├── mark.svg                  # original generic portfolio logo mark
│   ├── gameplay-*.webp           # original CS2-inspired images
│   ├── launcher-concept.webp    # original illustrative launcher artwork
│   └── development-*.webp        # conceptual engineering illustrations
└── README.md       # these instructions
```

**New: Image-led product promotions, CS2-inspired game artwork and engineering visuals.** All display assets are bundled locally as optimized WebP files. Product links point to the official Stray Bullet website for current listings; this GitHub Pages site does not process purchases.

**No frameworks, build tools, API keys or external dependencies.** The website uses HTML, CSS and JavaScript and works both locally and on GitHub Pages project URLs.

## Quick publishing instructions

1. On GitHub, create a **new public repository** named `stray-bullet-portfolio`. You can choose another name, but the Pages URL will change.
2. Upload **the files from inside this folder** to the repository's root (not an extra nested folder). Ensure `index.html` is in the root.
3. Commit the files to the `main` branch.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, then select branch **`main`** and folder **`/(root)`**. Save.
6. GitHub will publish your site. It may take several minutes to appear. Its typical URL would be:

   `https://luckycoder-deep.github.io/stray-bullet-portfolio/`

   This is an **expected URL**, not a live link until you create and publish the repository.

Official deployment reference: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Official Pages limits: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

## Before publishing

- **Team:** Replace contribution-area cards with real team profiles **only if the members agree** to having their names, roles, photos and other information published. No identities were invented.
- **Logo:** `assets/mark.svg` is an original *placeholder mark*, not a verified official Stray Bullet logo. Replace it with the official logo if desired.
- **Links:** Confirm the official website, public GitHub URL and forum link are current.
- **Screenshots:** The portfolio's interface art, gaming images and development gallery are **illustrative**. They are not verified screenshots of shipping app features or production dashboards. Replace with your own screenshots if preferred.
- **Products:** Product cards describe platform categories, not a promise that any particular game, app, feature, plan or price is currently available. Check the official Store before announcing specific app availability.
- **Image source:** Includes original artwork generated during this conversation and original development diagrams created for this portfolio. Do not imply affiliation with third-party game publishers.
- **Security:** Do not upload `.env`, production credentials, private source files, customer data or secrets. Any exposed live credentials in the original public repo should be revoked/rotated separately.
- **Copy review:** Confirm any wording against the shipped product before publishing and keep it up to date.

## Editing the portfolio

| Want to change | File |
|---|---|
| Headlines, portfolio text, cards, team roles | `index.html` |
| Colors, typography, layout, spacing | `styles.css` |
| Tabs, mobile navigation, theme toggle | `script.js` |
| Logo | `assets/mark.svg` |

The site uses **relative asset paths** so it will work in a GitHub Pages *project repository* subfolder.

## Privacy and implementation

There is no analytics script, visitor tracking, sign-in form or data collection by this site's own code. The local theme preference is stored in browser local storage. GitHub Pages itself has platform-level access logging per GitHub's privacy notice.

## Local preview

Either double-click `index.html`, or use a local static server:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080/`.
