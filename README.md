# Sylvia Sharp Studio

Content and marketing business website built with Astro.

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Development
```bash
npm install
npm run dev
```

Visit `http://localhost:3000` in your browser.

### Build for Production
```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── layouts/Layout.astro    # Main layout wrapper
├── pages/
│   ├── index.astro         # Homepage
│   ├── about.astro         # About page
│   └── clock.astro         # World Clock tool

.github/
└── workflows/
    └── deploy.yml          # Auto-deploy to GitHub Pages
```

## Pages

- **Home** (`/`) - Welcome and services overview
- **About** (`/about`) - About Sylvia Sharp Studio
- **World Clock** (`/clock`) - Live time zones display

## Deployment

This site automatically deploys to GitHub Pages when you push to the `main` branch!

Your site will be available at: `https://sylviasharp.github.io/sylviasharpstudio/`

## Customization

Edit the `.astro` files in `src/pages/` to customize your content!
