# Artist Lab Public Site

Public static site for Artist Lab.

This repository hosts the product home page and the static legal/support documents used by the app:

- Product home page
- Privacy Policy
- Terms of Use
- Support
- Third-Party Notices

It does not contain Artist Lab app source code, product roadmap, private screenshots, or private implementation details.

## Languages and app links

The existing root pages serve Brazilian Portuguese (`pt-BR`). Matching US English pages live under `en/`. Every page includes a link to its equivalent in the other language. Both versions share `styles.css` and the existing image assets.

The current public base URL is `https://lauromarinho.github.io/ArtistLab/`. The app opens `privacy.html`, `terms.html`, `support.html`, and `third-party-notices.html` at that root for Portuguese, or under `en/` for English. The retired `/PaletteArtist-Legal/` URLs return 404.

Support remains `artistlab.support@gmail.com` in both languages. The support composer includes the user's message and chosen attachment, without automatically adding device or app information.

Validation on 2026-09-09: all 10 HTML pages have matching language declarations, valid local links/anchors/assets, and working language switches. Mobile browser previews checked for home, privacy, and support. Publish this static site before distributing an app build that targets the new English URLs.
