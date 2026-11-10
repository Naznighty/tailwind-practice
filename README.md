# Saatchi (ساعتچی) — Watch Store Landing Page

A responsive, RTL Persian landing page for a watch store, built as a Tailwind CSS speed-practice project. It features a product grid, About and Contact sections, a custom color palette, and a dark mode toggle. It is a single static `index.html` file with no build step.

![Preview](./screenshots/preview.png)

> Add a screenshot at `screenshots/preview.png` (light and dark mode side by side works well).

## Features

- **Sticky navbar** with animated underline links and smooth scrolling to sections
- **Product cards** in a responsive grid (4 / 2 / 1 columns), equal height, with hover lift effect
- **About** section with three feature cards
- **Contact** section with business info and a message form
- **Dark mode** with a toggle button. It saves your choice in `localStorage`, falls back to the system theme, and avoids a flash on load
- **RTL layout** with the [Vazirmatn](https://fonts.google.com/specimen/Vazirmatn) Persian font
- **Custom brand palette** configured in `tailwind.config`
- **Accessible basics**: labels on inputs, `aria-label` on icon buttons, visible focus rings

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (Play CDN)
- Vanilla JavaScript (theme toggle, contact form)
- A small amount of custom CSS (card hover, nav underline)

## Color Palette

Based on this [Color Hunt palette](https://colorhunt.co/palette/faf7f3f0e4d3dcc5b2d9a299).

| Token | Hex | Usage |
| --- | --- | --- |
| `brand-50` | `#FAF7F3` | Page background, header |
| `brand-100` | `#F0E4D3` | Cards, sections |
| `brand-200` | `#DCC5B2` | Borders, image placeholders |
| `brand-500` | `#D9A299` | Accent, focus rings |
| `brand-600` | `#A8645B` | Buttons, logo, prices (darker shade for contrast) |

## Getting Started

No installation is needed.

```bash
git clone https://github.com/Naznighty/saatchi.git
cd saatchi
```

Then open `index.html` in your browser, or use a local server such as the VS Code **Live Server** extension.

An internet connection is required because Tailwind, the font, and the product images are loaded from external URLs.

## Project Structure

```
.
├── index.html
├── screenshots/
│   └── preview.png
└── README.md
```

## Customization

- **Colors:** edit the `brand`, `ink`, and `night` values in the `tailwind.config` block inside `<head>`.
- **Products:** duplicate or edit an `<article class="product-card ...">` block in the products section.
- **Contact info:** update the address, phone, and email inside the `#contact` section (the current values are placeholders).

## Author

**Nazanin Rahgozar** — [@Naznighty](https://github.com/Naznighty)
