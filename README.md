# Art Vision Studio — ArtVision DesiMuseum
### Indian folk-art canvas & CNC masterpiece store · Made in India

A premium, editorial art-gallery e-commerce website celebrating the civilisational
diversity of Bharat — from Warli and Madhubani to Pattachitra, Phad, Ajrak and
regional luxury wallpapers of 10 different places (Jaipur, Srinagar, Kerala,
Varanasi, Mysore, Kolkata, Mumbai, Bhuj, Odisha, Assam).

## Highlights
- **705-image living archive** — 176 live artworks (hero + 65 canvases + 110
  Nocturne & Vermillion Dawn print editions) + **529 "Coming soon" tiles**
  (257 Tribes-of-India portraits + 272 expansion-series pieces). Every tile
  carries a museum-style name label under the image. Drop a generated
  image into the folder with its exact filename and its tile goes live instantly —
  see **PROMPTS.md** for all 529 ready-to-use image prompts
- **65 canvas products** across Regions / Folk & craft / Nature & wildlife /
  Tribal traditions / Languages of India, with search + filters
- **Interactive Bharat map** — mouse-following radial colour reveal (vanilla JS,
  touch fallback included)
- **11 art series**: flat folk → framed → CNC impossible-frames → embossed glossy
  acrylic → real-room laser-engraved → acrylic paintings → creative concepts →
  backlit fabric/translite → neon tubes → frameless acrylic cutouts → laser-lit
  engraved acrylic → wall murals → regional luxury wallpapers
- **Click any canvas artwork → download dialog** with automatic **Art Vision
  Studio logo watermark** baked into the saved JPG (100% client-side canvas)
- Red studio band with brand line + Google Maps studio link
- Cart drawer, limited-time offer timer, sale/MRP pricing
- **Zero external dependencies** — no Google Fonts, no CDN libraries, no external
  images. 100% local assets, system font stacks (Arial Black / Georgia / system sans)

## Tech
Pure semantic HTML + organised CSS (single stylesheet, custom properties) +
vanilla JavaScript. Verified with `node --check` and a 34-assertion jsdom
DOM-execution suite (render, search, filters, cart, map interaction, timer).

## Structure
```
index.html            # the complete website (single file, inline CSS/JS)
logo_icon.png         # Art Vision Studio icon (favicon, footer)
logo_full.png         # Art Vision Studio horizontal logo (nav)
india_motif_hero.jpg  # hero Bharat map artwork
art_*.jpg             # 65 canvas artworks (11 series + wallpapers)
ed_night_*.jpg        # 65 Nocturne print editions
ed_dawn_*.jpg         # 45 Vermillion Dawn print editions
robots.txt            # crawler rules + sitemap pointer
sitemap.xml.template  # rename to sitemap.xml after going live
PROMPTS.md            # 529 ready-to-use prompts for the coming-soon archive
DEPLOY.md             # GitHub Pages / Netlify guide + 30-day traffic playbook
README.md  LICENSE  COPYRIGHT.md  CHANGELOG.md  .gitignore
original-index.html  # v1.0 original upload (history reference)
```

## Branding & contact
- **Brand:** Art Vision Studio — Production & Design
- **Email:** artvisioncnc@gmail.com
- **Instagram:** https://www.instagram.com/artvision_studion/
- **WhatsApp:** https://wa.me/919009001551
- **Pinterest:** https://in.pinterest.com/ranjansarkar83/

## Go live
See **DEPLOY.md** — GitHub Pages in 3 steps (repo → upload → Settings→Pages),
plus the 30-day customer-traffic playbook.

## License & copyright
Proprietary. © 2026 Art Vision Studio. All rights reserved. See **LICENSE** and
**COPYRIGHT.md**.
