<div align="center">

# SPENTA
### The Global Marketplace for Everything

*Real estate · Vehicles · Motorcycles · Jobs · Goods · Services — one showcase, every market.*

![Status](https://img.shields.io/badge/status-beta-8A5C1E?style=flat-square)
![React](https://img.shields.io/badge/React-18-149ECA?style=flat-square&logo=react&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-3D%20Globe-000000?style=flat-square&logo=three.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-styled-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white)
![i18n](https://img.shields.io/badge/i18n-EN%20%2F%20FA-E5B94E?style=flat-square)
![License](https://img.shields.io/badge/license-proprietary-lightgrey?style=flat-square)

</div>

---

## ✨ What is this

SPENTA is a full single-page marketplace application — not a template with placeholder screens, an actual working product: browse, filter, compare, message, bid, verify your identity, post a listing, and manage a seller dashboard, all wired up end to end.

It ships with a distinctive **"gallery / auction-house" visual identity** — gold corner-bracket hover frames, serif typography, lot numbering — instead of the generic classifieds look most marketplace templates share.

## 🖥️ Try it

No install needed to look around:

```bash
# open index.html directly, or serve it locally:
npx serve .
```

To run the full dev project (hot reload, etc.):

```bash
cd spenta-app
npm install
npm run dev
```

## 🎯 Highlights

| | |
|---|---|
| 🌍 **Interactive 3D globe** | Real markets plotted on a rotating Three.js globe — click a city for a live stats popup |
| ⌘K **Command palette** | Jump anywhere in the app from the keyboard, no mouse required |
| 🈺 **Full i18n** | English + Persian, RTL/LTR-aware layout, not just translated strings |
| 🛡️ **Trust & verification** | Multi-step signup, phone OTP, ID verification with a redesigned membership-card UI |
| 💰 **Live market data** | Real exchange rates, gold, and crypto prices — auto-refreshing, no fake numbers |
| 🔨 **Auctions** | Bidding mode per listing with live bid history |
| 📄 **PDF export** | Print-ready "lot certificate" for any listing |
| 📊 **Seller insights** | Views-over-time chart, dashboard analytics |
| 🖼️ **Zero external images** | Every photo is generated inline (SVG) — nothing to load, nothing that can be blocked |
| ♿ **Accessible** | Keyboard nav, focus states, checked contrast, `prefers-reduced-motion` support |

## 📦 What's inside

```
├── index.html            ← standalone build — open it, done. No install.
├── bazaru.tsx            ← the source component (single file, ~5,400 lines)
└── spenta-app/           ← full Vite project (for local dev / real deployment)
    ├── src/App.jsx
    ├── src/main.jsx       ← includes a localStorage polyfill for the app's storage layer
    └── ...
```

## 🚀 Deploy it

**Easiest — zero build, zero terminal:**
Upload `index.html` to a GitHub repo → Settings → Pages → Deploy from branch → done. Live in ~2 minutes.

**Full project — for ongoing development:**
Push `spenta-app/` to GitHub → connect the repo on [Netlify](https://netlify.com) or [Cloudflare Pages](https://pages.cloudflare.com) → it builds and deploys automatically on every push.

## 🧱 Stack

`React 18` · `Three.js` · `Recharts` · `Tailwind CSS` · `lucide-react` — no backend required to run as-is.

## 🔍 Demo vs. real

This is a **beta / demo build**. Everything you see works, but a few things are intentionally simulated rather than wired to a live backend — see `SPENTA-feature-overview.md` for the full breakdown of what to swap in before a real public launch (auth, listings database, payments).

---

<div align="center">
<sub>Built with Claude · SPENTA © 2026</sub>
</div>
