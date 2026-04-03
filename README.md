# Omaré — Sacha Inchi Brand Website

A premium multi-page marketing website for **Omaré**, a health and wellness brand bringing the Amazonian superfood **Sacha Inchi** to health-conscious consumers worldwide.

Live site: [arenascode.github.io/sachaInchiFV](https://arenascode.github.io/sachaInchiFV)

---

## About the Project

Omaré celebrates the nutritional and ancestral heritage of Sacha Inchi — a nutrient-dense seed from the Amazon rainforest rich in Omega 3, 6, and 9. The website tells the brand's story through immersive design, scroll animations, bilingual content, and interactive product sections.

---

## Tech Stack

| Category | Tools |
|---|---|
| Build tool | [Vite 6](https://vitejs.dev/) |
| Reactivity | [Alpine.js 3](https://alpinejs.dev/) |
| Styling | [Tailwind CSS 3](https://tailwindcss.com/) + [DaisyUI 4](https://daisyui.com/) |
| Animations | [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) |
| Charts | [Chart.js 4](https://www.chartjs.org/) |
| Deployment | [GitHub Pages](https://pages.github.com/) via `gh-pages` |

---

## Pages

| Route | Description |
|---|---|
| `/` | Homepage — hero, product benefits, packaging, sustainability |
| `/src/pages/about.html` | Brand story, founder info, product deep-dive |
| `/src/pages/mission.html` | Company mission and values |
| `/src/pages/bosqueSeco.html` | Regional product page |

---

## Features

- **Bilingual** — English / Spanish toggle with flag icons
- **Interactive benefit cards** — expandable modals for each health benefit (cardiovascular, cognitive, immune support, and more)
- **Scroll animations** — powered by AOS
- **Parallax effects** — layered background motion on scroll
- **Nutritional charts** — Chart.js data visualizations
- **Mobile-first** — responsive layout with hamburger menu and adaptive grids
- **Optimized assets** — WebP images, custom fonts, and video backgrounds

---

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Preview production build
npm run preview
```

---

## Build & Deploy

```bash
# Production build (output to dist/)
npm run build

# Build for GitHub Pages
npm run build:gh

# Deploy to GitHub Pages
npm run deploy
```

> `npm run deploy` automatically runs `build:gh` before pushing to the `gh-pages` branch.

---

## Project Structure

```
sachaInchiFV/
├── index.html              # Homepage
├── vite.config.js          # Multi-page Vite configuration
├── tailwind.config.js      # Custom theme (colors, fonts, breakpoints)
├── public/
│   └── assets/
│       ├── fonts/          # BrownSugar, Lato, Lora
│       ├── icons/          # SVG/PNG icons
│       ├── img/            # ~82 optimized images (WebP)
│       └── video/          # Video assets
└── src/
    ├── main.js             # Navigation, language toggle, modals
    ├── moreInfo.js         # About page logic and Chart.js integration
    ├── style.css           # Global styles
    ├── pages/
    │   ├── about.html
    │   ├── mission.html
    │   └── bosqueSeco.html
    └── style/
        ├── about.css
        └── mission.css
```

---

## Design System

**Colors**

| Name | Hex |
|---|---|
| Deep Green (primary) | `#1b4d20` |
| Gold (accent) | `#f6ba02` |
| Cerulean | custom |
| Sand / Cream | custom |

**Typography**
- `BrownSugar` — display / brand
- `Lora` — serif body
- `Lato` — sans-serif UI

**Breakpoints**
- Standard Tailwind breakpoints + custom `1.5xl` at `1440px`

---

## License

All rights reserved. Omaré brand assets and content are proprietary.
