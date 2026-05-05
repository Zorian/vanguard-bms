# OD Controls

Website for **OD Controls** (On Demand Controls) — London's on-demand building management systems specialists.

Trading as OD Controls · OD Controls Ltd (incorporation pending).

> Repo currently named `vanguard-bms` for legacy URL. Will rename to `od-controls` once the domain and Companies House are confirmed.

## Stack
Single-page static site. Vanilla HTML/CSS/JS. No build step. Deploys to GitHub Pages.

## Structure
```
.
├── index.html         # the whole site
├── img/               # WebP photography + brand assets
│   ├── od-lockup-light.png   # logo for dark backgrounds (header, footer)
│   ├── od-lockup-dark.png    # logo for light backgrounds
│   ├── od-badge-light.png    # badge mark only (light)
│   ├── od-badge-dark.png     # badge mark only (dark)
│   ├── od-favicon.png        # 256px favicon
│   └── og-image.png          # 1200x630 social preview
└── README.md
```

## Local preview
Just open `index.html` in a browser, or:
```
python3 -m http.server 8080
```
then visit http://localhost:8080

## Placeholders to replace before launch
- [ ] Phone number — currently `020 0000 0000`
- [ ] Companies House registration number — currently `TBC`
- [ ] Domain — point `odcontrols.co.uk` at GitHub Pages
- [ ] Repo rename — `vanguard-bms` → `od-controls` (URL becomes `zorian.github.io/od-controls`)

## Deploy
Pushes to `main` auto-deploy via GitHub Pages.
