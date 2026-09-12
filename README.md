# শব্দ · Shobdo

**Offline-first Bangla ⇄ English Dictionary**

Shobdo is a lightweight Progressive Web App (PWA) that gives you instant access to over **100,000** English–Bangla and Bangla–English dictionary entries — completely offline after the first load.

![Shobdo](icon-512.png)

## Features

- **Fully offline** — Once loaded, the entire dictionary works without an internet connection
- **Bidirectional search**
  - English → Bangla
  - Bangla → English
  - All (search both directions at once)
- **Fast client-side search** with ranking (exact matches first)
- **Alphabet browsing** (A–Z filter)
- **Part-of-speech badges** (where available)
- **Installable** as a native-like app on Android, iOS, Windows, and macOS
- **Clean, readable design** with proper Bangla typography
- **Offline indicator** and install prompt

## Tech Stack

- Pure HTML / CSS / Vanilla JavaScript (no frameworks)
- Service Worker for offline caching
- Web App Manifest
- Google Fonts: *Tiro Bangla*, *Hind Siliguri*, *Fraunces*, *Inter*

## Getting Started

### Option 1: Just open it

1. Download or clone this repository
2. Open `index.html` in a modern browser  
   *(Note: Service Worker requires HTTPS or `localhost`)*

### Option 2: Serve locally (recommended)

```bash
# Using Python
python -m http.server 8000

# Or using Node
npx serve .
