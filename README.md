# perioparrot.tooshel.com

Marketing site for **PerioParrot** (formerly PerioVox), voice-input perio charting from DPSystems, LLC. The app
itself lives in the private repo dbacks95fan/periovox; this repo is only the public website. The old
periovox.tooshel.com site (tooshel/periovox-web) is left up as it was.

One hand-written page, no build step: edit `index.html`, commit, push. GitHub Pages serves the repo root; `CNAME`
keeps the custom domain. DNS: `perioparrot` CNAME to tooshel.github.io on the tooshel.com Cloudflare zone
(DNS-only).

## The parrot

`img/parrot.svg` is the mascot (a blue-and-gold macaw perched on a perio probe) and `img/icon.svg` the app-style
icon. Both are hand-drawn SVG, so they scale to any size and are easy to recolor. `favicon.png`,
`apple-touch-icon.png`, and `og.png` (the social share image) are rendered from them with headless Chrome.

## Keep the claims honest

Keep the site in step with the app's docs (README, user guide, EULA): local speech processing, nothing sent to
DPSystems, keystroke-only (no practice-management database or API access), Windows 10/11, and the Dentrix
trademark disclaimer in the footer. No pricing or download link until DPSystems is ready to sell.
