# support

Support and legal pages for both apps, served by GitHub Pages.

Live at https://sharonlouisedev.github.io/support/

## Bracket Maker — at the root

- `index.html` — support landing page, links to both apps
- `help.html` — frequently asked questions
- `privacy.html` — privacy policy
- `terms.html` — terms of use

## Recipe Keeper — in `recipe-keeper/`

- `recipe-keeper/index.html` — landing page
- `recipe-keeper/help.html` — support and FAQ (App Store Connect: Support URL)
- `recipe-keeper/privacy.html` — privacy policy (App Store Connect: Privacy Policy URL)
- `recipe-keeper/terms.html` — terms of use

Recipe Keeper needs its own documents rather than the ones at the root: it syncs
through iCloud, it fetches pages from third-party websites when a link is
imported, and it uses the camera and photo library. None of that is true of
Bracket Maker, and a privacy policy that omits it is wrong rather than merely
short.

`.nojekyll` stops GitHub running the files through Jekyll.
