# Yi-Hsien Huang — Academic Website V2.0

Free static academic website for GitHub Pages, prepared for `huang4343.github.io`.

## Publishing (browser only)

1. Download and unzip `Academic_Website_V2_GitHub_Pages.zip`.
2. Open https://github.com/huang4343/huang4343.github.io
3. Use **Add file > Upload files** and drag **the contents** of the unzipped `academic_site_v2` folder to the repository root. Do not upload the containing folder itself.
4. Commit directly to `main`. Replace `index.html` when GitHub indicates the same file already exists (the web interface may not allow overwrite by upload; if so, open `index.html`, choose Edit, replace its content with the new `index.html` content, and commit; upload the other files normally).
5. Confirm **Settings > Pages > Deploy from a branch > main > /(root)**. Wait for deployment and refresh https://huang4343.github.io/.
6. Test the navigation links on desktop and phone.

## Website structure

- `index.html` — home
- `about.html`, `research.html`, `publications.html`, `data.html`, `teaching.html`, `industry.html`, `contact.html`
- `assets/style.css` — theme / responsive styling
- `assets/site.js` — minor progressive enhancement
- `data/publications.json` — **editorial staging file, not verified published bibliography**

## Editorial checks before publishing personal updates

- Confirm appointment title, school permissions, dates and how affiliations should be represented.
- Confirm exact bibliographic metadata and publication status for each paper.
- Confirm Zenodo record title, licensing, version and public accessibility.
- Insert only personally approved contact addresses and profile links.
- Never include confidential research data, review correspondence, or restricted teaching material.

## Notes

- No build tooling, accounts, paid hosting, CDN, tracking or third-party scripts required.
- Content is editable using any text editor and can be deployed as ordinary static files.
- `data/publications.json` is a starter template, not an automatically rendered feed.
