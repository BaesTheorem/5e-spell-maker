# 5e Spell Maker

A browser-based tool that formats homebrew Dungeons & Dragons 5th Edition spells to look like they came straight out of a sourcebook. Fill in the spell's details, accepts inline HTML for formatting, and export the finished card as an image.

> **This is a preservation mirror, not the original.** All credit goes to the original creator, **Haasio**. This repository exists only to keep the project from disappearing if the itch.io page ever goes down.

## Original source

- **Creator:** Haasio
- **Original page:** https://haasio.itch.io/5espellcard
- **Status:** No longer actively developed (per the creator's own note on itch.io: *"i'm not currently working on this project anymore"*).
- **Original tagline:** *"Tired of formatting homebrew spells on Google docs?"*
- The creator tagged the project **"No generative AI was used."**

## Running it

It's a fully static, self-contained page. Either:

- Open `index.html` directly in a browser, **or**
- Serve the folder locally, e.g. `python3 -m http.server` then visit http://localhost:8000

## Contents

| File | Purpose |
|------|---------|
| `index.html` | The tool itself (title: "5e Spellcard Generator") |
| `stylesheet.css` | Styling, including the book-page background and Lora font face |
| `jquer.js` | jQuery (bundled by the original author) |
| `html2canvas.js` | Renders the spell card to a downloadable image |
| `background.jpg` | The parchment-style card background |
| `Lora Regular 400.ttf` | The Lora serif font used on cards |
| `icon.svg` / `icon-1024.png` / `icon.icns` | App icon added by this archive (not part of the original) |
| `favicon-32.png` / `apple-touch-icon.png` | Browser-tab / home-screen icons added by this archive |

## Attribution & license

No explicit license was published with the original tool. This mirror is shared for **archival and preservation purposes**, with full attribution to Haasio. If you are the original author and would like this taken down or relicensed, please open an issue.

The bundled third-party components retain their own licenses: jQuery (MIT), html2canvas (MIT), and the [Lora font](https://github.com/cyrealtype/Lora-Cyrillic) (SIL Open Font License).

*Dungeons & Dragons is a trademark of Wizards of the Coast. This tool is unofficial fan content and is not affiliated with or endorsed by Wizards of the Coast.*

---

*Archived on 2026-06-07. The tool's own files (`index.html`, `stylesheet.css`, `jquer.js`, `html2canvas.js`, `background.jpg`, `Lora Regular 400.ttf`) were downloaded verbatim from the live itch.io HTML build (`html-classic.itch.zone/html/7101371/`). The only changes by this archive are the added icon files and two `<link rel="icon">` lines in `index.html`.*
