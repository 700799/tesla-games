# tesla-games

Touch-friendly browser games sized for the Tesla touchscreen (they work on any desktop, tablet or phone too).
Every game is plain HTML/JS with no build step and no dependencies.

## Games

| Game | Path | Description |
|------|------|-------------|
| **Hole City** | [`hole/`](hole/) | A hole.io-style game starring hungry cute monsters. Your monster's open mouth is the hole: gobble people, cars, trees and eventually skyscrapers to grow, and be the biggest monster when the 2-minute timer runs out. Six AI rival monsters compete with you, and bigger monsters can gobble smaller ones. |

### Hole City controls
- **Touch / mouse:** drag anywhere on the screen (floating joystick)
- **Keyboard:** WASD or arrow keys

Objects only fall in once they're small enough for your hole (start with people and cones, then cars, buses, houses, shops, office blocks, skyscrapers). Gobbling a rival monster steals part of its size; if you get swallowed you respawn after 3 seconds at half size. Your best score is saved in the browser.

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Playing in a Tesla

The car's browser only works while parked. Host the repo on any static host (GitHub Pages, Vercel, Netlify, Cloudflare Pages) and open the URL in the in-car browser.

For GitHub Pages: repo **Settings → Pages → Deploy from branch → `main` / root**.
