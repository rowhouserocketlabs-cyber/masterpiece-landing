# Masterpiece Registry — Landing Page

Static landing page for masterpieceregistry.com, deployed via Vercel.

## Setup

### 1. Email capture (Formspree)
1. Go to [formspree.io](https://formspree.io) → sign up free
2. Create a new form
3. Copy the form ID (looks like `xpwzabcd`)
4. In `index.html`, replace `YOUR_FORM_ID` with your ID

### 2. Screenshots
Add these images to the `img/` folder:
- `img/hero.jpg` — Full portfolio page (gallery-dark template), 1400px wide
- `img/portfolio.jpg` — Artwork grid on public portfolio, 1200px wide
- `img/inventory.jpg` — Artwork management dashboard in grid view, 1200px wide

The page shows a "Screenshot coming soon" placeholder if images are missing.

### 3. Deploy to Vercel
1. Push this folder to a GitHub repo
2. In Vercel → New Project → import that repo
3. No build settings needed (static HTML)
4. Add custom domain: masterpieceregistry.com
