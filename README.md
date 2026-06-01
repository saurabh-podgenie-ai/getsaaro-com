# getsaaro.com

Marketing site for [Saaro](https://getsaaro.com) — the podcast app where you shape every listen.

## Structure

```
getsaaro-com/
├── CNAME                  # getsaaro.com (GitHub Pages custom domain)
├── index.html             # Home page
├── demo.html              # Screenshots + animation placeholder
├── privacy.html           # Privacy Policy
├── terms.html             # Terms of Service
├── support.html           # Support / FAQ
├── creators.html          # Creator opt-out page
├── changelog.html         # What's new
├── styles.css             # Shared styling
├── images/                # Screenshots and demo assets (add manually)
│   └── .gitkeep
├── favicon.ico            # TODO: add manually
└── og-image.png           # TODO: add manually (1200×630)
```

Pure static HTML + CSS. No build step. Deployed via GitHub Pages.

## Deployment

This repo is configured for GitHub Pages with a custom domain (`CNAME` file). Push to `main` to deploy.

DNS is configured at Namecheap:
- Four `A` records for `@` pointing to GitHub Pages IPs
- One `CNAME` record for `www` pointing to `saurabh-podgenie-ai.github.io`

## TODOs before public launch

- [ ] Add `favicon.ico`
- [ ] Add `og-image.png` (1200×630)
- [ ] Add screenshots to `/images/` (see `demo.html` for expected filenames)
- [ ] Deploy `submitWaitlist` Firebase Cloud Function (separate spec)
- [ ] Record demo animation and replace placeholder in `demo.html`
- [ ] Have privacy policy reviewed by a lawyer before wide public launch
