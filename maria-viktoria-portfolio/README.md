# Maria-Viktoria — Portfolio

Portfolio website of Maria-Viktoria, Junior UX/UI Designer based in Kyiv.

🔗 **Live:** [maria-viktoria.vercel.app](https://maria-viktoria.vercel.app)  
🎨 **Figma:** [Design file](https://www.figma.com/design/c2S1jR4wR7i3jGdqmz8c94/Untitled)

---

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| About | `about.html` |
| Cases | `cases.html` |
| Case: Tour of Odesa Region | `case-odesa.html` |
| Case: Ceramics Online Shop | `case-ceramics.html` |
| Contact | `contact.html` |

## Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, grid, flexbox, no frameworks
- **Vanilla JS** — hamburger menu, scroll effects
- **Google Fonts** — Outfit (300, 400, 600)
- **Vercel** — deployment via GitHub

## Structure

```
maria-viktoria-portfolio/
├── index.html
├── about.html
├── cases.html
├── case-odesa.html
├── case-ceramics.html
├── contact.html
├── css/
│   ├── style.css        ← global styles + design tokens
│   ├── home.css
│   ├── about.css
│   ├── cases.css
│   ├── case.css
│   └── contact.css
├── js/
│   └── main.js
└── assets/
    └── images/
        ├── collage/
        ├── odesa/
        └── ceramics/
```

## Deploy on Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import Git Repository
3. Select repo → Vercel auto-detects static site
4. Every push to `main` triggers auto-deploy ✅

## Images to add

Before deploying, add your screenshots to `assets/images/`:

- `collage/about-collage.jpg` — collage photo for About page
- `odesa/hero.jpg` — full page screenshot
- `odesa/screen-hero.jpg`, `screen-programme.jpg`, `screen-mobile.jpg`
- `ceramics/hero.jpg` — full page screenshot
- `ceramics/screen-homepage.jpg`, `screen-catalog.jpg`, `screen-product.jpg`, `ui-kit.jpg`

**Recommended:** export as WebP, max width 1600px, compress to under 200kb each.
