# LS Invoice — Professional Invoice Manager

> A free, client-side professional invoice manager — create, customize, preview, and print invoices right in your browser. No sign-up, no backend, your data stays on your device.

## ✨ Features

- **Invoice builder** — add line items with quantities, rates, taxes, and discounts
- **Live preview** — see the invoice update in real time as you type
- **Client & company details** — business info, invoice numbering, dates
- **Tax & currency support** — configurable tax rates and currency formatting
- **Print / Save as PDF** — browser print styles optimized for A4 output
- **LocalStorage persistence** — invoices saved on your device, works offline
- **Fully responsive** — works on desktop, tablet, and mobile
- **100% free, no login** — everything runs client-side in a single page

## 🛠 Tech Stack

- HTML5 / CSS3 / JavaScript (vanilla)
- Tailwind CSS (CDN) for styling
- Lucide icons
- Google Fonts (Inter, Playfair Display, Roboto Mono)

## 🚀 Quick Start

No build step, no dependencies to install — it is a single static page:

```bash
# Option 1: just open it
open index.html          # or double-click index.html

# Option 2: serve locally
npx serve .
# then visit http://localhost:3000
```

## 📁 Project Structure

```
LS-Invoice-Professional-Invoice-Manager/
├── index.html      # the entire app (markup, styles, logic)
└── README.md
```

Everything — the editor UI, invoice preview, print stylesheet, and
localStorage persistence — lives in `index.html`.

## 🌐 Deploy

This is a static site with no build step. Any static host works:

- **GitHub Pages** — repo Settings → Pages, branch `main`, path `/`
- **Cloudflare Pages / Netlify / Vercel** — drag-and-drop or connect the repo

## 📄 License

MIT — free to use, modify, and share.

---

**Built by [Girish Lade](https://ladestack.in)** — more projects at [ladestack.in](https://ladestack.in)
