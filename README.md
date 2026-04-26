# Vanguard BMS

Website for **Vanguard BMS** — London's building management systems specialists.

Trading as Vanguard BMS · Vanguard Building Controls Ltd (incorporation pending).

## Stack
Single-page static site. Vanilla HTML/CSS/JS. No build step. Deploys to GitHub Pages.

## Structure
```
.
├── index.html         # the whole site
├── img/               # WebP-optimised photography
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
- [ ] Domain — point `vanguardbms.co.uk` at GitHub Pages

## Deploy
Pushes to `main` auto-deploy via GitHub Pages.
