# Carbon-Radio
Songs for travelers moving by myth and memory
# Cosmic Station

A minimal live radio station page built for GitHub Pages.

Press play. Let it run. No distractions.

## What this is
- Static HTML + CSS + JS
- Designed for live streams (Icecast / Shoutcast / AzuraCast)
- Works on desktop and mobile
- No build step, no frameworks

## How it works
The page loads a live audio stream using the HTML `<audio>` element.

To change the stream:
1. Open `index.html`
2. Replace `STREAM_URL_HERE` with your stream URL
3. Commit and push

## Deploy on GitHub Pages
1. Go to **Settings → Pages**
2. Source: `Deploy from branch`
3. Branch: `main`
4. Folder: `/ (root)`
5. Save

Your station will be live at:
`https://username.github.io/repo-name`

## Notes
- Autoplay is blocked by browsers — users must click Play
- Some streams require `.m3u` or `.pls` URLs
- CORS issues are stream-side, not site-side

## License
MIT — see `LICENSE`
