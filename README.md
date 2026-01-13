# GlitchGallery

A mesmerizing infinite scroll gallery featuring glitch art, digital art, and NFTs from multiple sources.

## Features

- **Multi-Source Content**: Pulls from Tenor, Giphy, Reddit, objkt.com (Tezos NFTs), Pexels, NASA, DeviantArt, Tumblr, Bluesky, Archive.org, and Wikipedia
- **Dopamine Rush Mode**: Multiple rows scrolling in alternating directions
- **NFT Integration**: Shows pricing and availability for objkt.com listings with direct purchase links
- **Smart Filters**: Filter by glitch, VHS, cyberpunk, trippy, and more
- **Artist Search**: Search by specific artists or objkt.com wallet addresses
- **Save Collection**: Bookmark your favorite pieces (stored locally)
- **Responsive**: Works on desktop and mobile

## Live Demo

Visit: `https://YOUR_USERNAME.github.io/GlitchGallery/`

## Usage

Just open `index.html` in a browser or deploy to GitHub Pages.

### Controls
- **Scroll Speed**: Adjust auto-scroll speed
- **Card Size**: Change the size of artwork cards
- **Dopamine Rush**: Toggle chaotic multi-row mode
- **Filters**: Click to open filter panel
- **Settings**: Adjust source weights

## Data Privacy

All saved items and settings are stored locally in your browser using localStorage. Nothing is sent to any server.

## Known Issues / TODO

**API Sources Needing Fixes:**

- [ ] **Bluesky** - CORS blocked (needs backend proxy or server-side fetch)
- [ ] **Archive.org** - CORS blocked (needs backend proxy or server-side fetch)
- [ ] **Pexels** - API key expired/invalid (401 error - need new API key)
- [ ] **Tumblr** - Rate limited (429 error - hitting API limits, may need auth or caching)

**Working Sources:**
- [x] Tenor
- [x] Giphy
- [x] objkt.com (Tezos NFTs)
- [x] NASA
- [x] Wikipedia
- [x] DeviantArt
- [x] Reddit (partial - some CORS issues)

## License

MIT
