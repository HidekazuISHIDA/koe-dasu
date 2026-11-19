# こえだす

A web app that reads typed text aloud in Japanese right away.
It uses the speech engine built into the browser (Web Speech API), so it is free, needs no API key and no server, and keeps working offline.

## Features
- Reads the text aloud automatically once typing stops for a set time (0.3–5 seconds)
- Waits while Japanese input is still being converted (IME), so it doesn't read half-finished words
- Enter reads immediately; Shift+Enter adds a line break; Esc stops
- Saved phrases (tap to read, add/remove your own)
- Reading history (tap to replay)
- Female / Male / All switch for the voice (with Edge, Male uses Keita and Female uses Nanami)
- Adjustable speed, pitch, volume and voice (settings are saved in the browser)
- Can be added to the home screen and used like an app (PWA)

## Publishing on GitHub Pages
1. Create a new public repository on GitHub (for example `koe-dasu`)
2. Upload the 4 files in this folder (`index.html` `manifest.json` `icon.svg` `sw.js`)
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)` → Save
4. After a few minutes it is live at `https://<username>.github.io/koe-dasu/`

## For the most natural voice
| Environment | Recommended voice |
|---|---|
| Windows / Mac **Edge** | Microsoft Nanami Online (Natural): the most natural |
| Chrome | Google 日本語 |
| iPhone / Mac Safari | Kyoko / O-ren (Enhanced/Premium versions are better) |

To add a high-quality voice on iPhone/Mac:
Settings → Accessibility → Spoken Content (Read & Speak) → Voices → Japanese → download Kyoko (Enhanced) or similar
