# AuraMC Store

A clean, responsive store page for the **AuraMC** Minecraft network — displaying VIP, MVP, and IMMORTAL rank kits with pricing, features, and a comparison table.

Built with vanilla HTML, CSS, and JavaScript. No build tools or frameworks required.

## Features

- Glassmorphism UI with animated background orbs and firefly particles
- Responsive layout — works on mobile, tablet, and desktop
- Live player count via the [mcsrvstat.us](https://mcsrvstat.us) API
- One-click IP copy with toast notification
- Rank comparison table (VIP / MVP / IMMORTAL)
- Discord ticket purchase flow

## Usage

Just open `index.html` in any browser — no server or build step needed.

To deploy, upload all files to any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

```
auramc-store/
├── index.html        # Main store page
├── logo.png          # AuraMC logo
├── backgroundimg.png # Background wallpaper
├── discord.png       # Discord icon
├── vip.png           # VIP kit preview
├── mvp.png           # MVP kit preview
└── immortal.png      # IMMORTAL kit preview
```

## Customisation

All rank details, prices, and Discord links are in `index.html`. Search for the relevant section (VIP / MVP / IMMORTAL) to update kit contents, commands, or pricing. The Discord invite link (`https://discord.gg/3FwP5hgsUb`) appears in a few places — replace all instances with your own.

## License

MIT — see [LICENSE](./LICENSE) for details.

> Not affiliated with Mojang Studios or Microsoft.
