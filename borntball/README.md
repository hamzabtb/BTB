# Born to Ball — Creative Club

A one-page website for Born to Ball Creative Club.

## Structure

```
/
├── index.html                  # Main website
├── Logo_Animation_Draft_2.mp4  # Preloader video
├── fonts/
│   ├── F37Judge-Bold.woff
│   ├── SpaceGrotesk-Bold.woff2
│   ├── SpaceGrotesk-Light.woff2
│   ├── SpaceGrotesk-Medium.woff2
│   ├── SpaceGrotesk-Regular.woff2
│   └── SpaceGrotesk_wght_.woff2
└── README.md
```

## Sections

- **[Home]** — Hero with preloader animation
- **[About]** — Full-screen typographic statement
- **[Team]** — Ruth, Hannah, Kristy, Hamza
- **[Experience]** — 40 years combined
- **[Services]** — Brand & Creative Strategy, Content & Campaigns, Sport Partnerships & Activations, PR & Earned Media
- **[Connect]** — Contact

## Typefaces

- **F37 Judge Bold** — Headlines & display text
- **Space Grotesk** — Body copy & sub-headings

## Deployment

Works as a static site. Deploy to any static host:

- **GitHub Pages** — Push to `main`, enable Pages in repo settings (source: root)
- **Netlify** — Drag and drop the project folder
- **Vercel** — Connect repo, deploy automatically

## Local Development

No build step required. Open `index.html` directly in a browser, or serve locally:

```bash
npx serve .
# or
python3 -m http.server 8000
```

> **Note:** Fonts must be served over HTTP — opening `index.html` directly via `file://` may block font loading in some browsers due to CORS. Use a local server for development.
