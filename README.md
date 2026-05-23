# Hobileht — Minu CS2 Statistika

A personal Counter-Strike 2 (CS2) statistics and highlights website built with HTML and CSS. The site showcases match history, key performance stats, and highlight clips in a clean, responsive layout — all written in Estonian.

## Features

- **Overview stats** — K/D ratio, win rate, and total matches played displayed on the homepage
- **Best moments** — a video gallery of personal highlight clips from various maps and matches
- **Recent matches** — a match history section with per-game stats (kills, deaths, K/D, MVPs) for maps like Mirage, Inferno, Dust 2, Nuke, Overpass, and Vertigo
- **Contact & social** — links to Twitch and YouTube, plus a contact email
- **Responsive design** — separate mobile stylesheet for screens under 860px wide

## Tech Stack

- HTML5
- CSS3 (desktop + mobile stylesheets)
- Font Awesome icons (via CDN)

## Project Structure

```
hobileht/
├── index.html        # Main page
├── css/
│   ├── style.css     # Desktop styles
│   └── mobile.css    # Mobile styles (max-width: 860px)
└── assets/
    ├── video1.mp4    # Highlight clip — montage
    ├── video2.mp4    # Highlight clip — Mirage Desert Eagle
    ├── video3.mp4    # Highlight clip — Dust 2 AK-47
    ├── video4.mp4    # Highlight clip — Mirage headshots
    ├── video5.mp4    # Highlight clip — Vertigo deathmatch
    └── video6.mp4    # Highlight clip — Dust 2 deathmatch
```

## Getting Started

No build tools or dependencies required — just open `index.html` in a browser.

```bash
git clone https://github.com/111markus/hobileht.git
cd hobileht
open index.html
```

## Pages / Sections

| Section | Description |
|---|---|
| `#kodu` | Homepage with hero text and stats overview |
| `#PH` | Parimad hetked — best highlight clips |
| `#VM` | Viimased mängud — recent match results |
| `#Kontakt` | Contact info and social media links |

## License

Personal project — feel free to use as a template for your own stats page.
