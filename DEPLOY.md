# 🚀 FINAL GUIDE — ArtVision DesiMuseum (Art Vision Studio) ko LIVE karna

Site **100% static** hai (index.html + images + docs). Checkout **WhatsApp** se hota hai
(isliye koi backend/server/database zaroori NAHI — free hosting par poori e-commerce chalti hai).

## 📁 Final files (jo upload karni hain)
```
index.html              # poori website (CSS/JS inline) — 176 live + 529 coming-soon tiles
logo_icon.png           # favicon + footer logo (transparent)
logo_full.png           # nav logo (transparent)
india_motif_hero.jpg    # interactive Bharat map
art_*.jpg (175)         # saare artworks (folk/minimal/UV/series)
robots.txt              # crawler rules
sitemap.xml.template    # live hone baad sitemap.xml naam se rename karo, domain daalo
PROMPTS.md              # 529 coming-soon prompts (exact filenames ke saath)
README.md · LICENSE · COPYRIGHT.md · CHANGELOG.md
```
(`original-index.html` sirf history reference hai — upload optional. `ed_*` files ab koi nahi bachin.)

## Step 1 — GitHub repo
1. github.com → **+** → **New repository** → name `INDIAN-FOLK-ART-PLAYING-CARDS` (ya `rjsarkar83.github.io/ArtVision_DesiMuseum` for clean URL) → **Public** → Create
2. Ya command line se (repo already local git me committed hai):
```bash
cd desi-deck
git remote add origin https://github.com/YOUR-USERNAME/desi-deck.git
git branch -M main
git push -u origin main
```
(Browser se karna ho to repo page par **uploading an existing file** → saari files drag-drop → Commit)

## Step 2 — GitHub Pages on
1. Repo → **Settings → Pages**
2. Source: **Deploy from a branch** → Branch **main** → Folder **/ (root)** → Save
3. 1–2 min me live: `https://YOUR-USERNAME.github.io/desi-deck/`

## Step 3 — E-commerce check-list (live hone ke baad)
- ✅ Add to Bag → drawer → **Checkout on WhatsApp** → order message seedha **+91 90090 01551** par
- ✅ Contacts footer me: email / Instagram / WhatsApp / Pinterest
- ✅ Studio map band (Google Maps link)
- ✅ Search + 12 collections (6 categories samet: General/OBC/SC/ST/EWS/Creamy-NonCreamy)
- ✅ 24hr daily rotation — grid har din naye artworks dikhata hai
- ✅ Kisi bhi artwork par click → watermarked download
- ⬜ Payments upgrade chahiye to baad me Razorpay/UPI QR footer me laga sakte ho (static me QR image kaafi hai)

## Step 4 — SEO
1. `sitemap.xml.template` me `https://YOUR-USERNAME.github.io/desi-deck/` daal kar **sitemap.xml** save karo
2. Google Search Console me property add karke sitemap submit karo
3. `robots.txt` already sitemap ki taraf point karta hai

## Step 5 — Coming-soon images live karna (PROMPTS.md)
1. PROMPTS.md se prompt copy karo → kisi bhi AI image tool me generate karo
2. Compress: `PIL: thumbnail((1200,1200)), quality=82, progressive` 
3. **Exact filename** se repo/folder me daalo → push → tile khud live (koi code change nahi)
4. Arena agent se karwana ho: *"PROMPTS.md ke A1–A10 generate karo"* (10/turn)

## 📈 30-din traffic playbook (short)
- **Din 1–3:** Instagram @artvision_studion + Pinterest par 9 posts (artwork + story caption), profile me site link
- **Din 4–10:** roz 1 Reel/Short — ek artwork ki 15-sec kahani (folk art = high-share content)
- **Din 11–20:** WhatsApp Broadcast/Status par daily pick (site ka 24hr pick use karo); local Indore groups + craft communities
- **Din 21–30:** 3 folk-art Facebook/Reddit communities me museum-story post; Pinterest pins roz 2
- **Har tyohar:** Diwali/Chhath/Pongal par themed artwork push karo (rotation pool me sab hai)
- **Offline:** QR-code wala visiting card — scan → site; exhibitions/haat me tablet par site chalayen

## 🔒 License
Proprietary © Art Vision Studio — see LICENSE & COPYRIGHT.md. Artwork resale/AI-training prohibited.

## 📊 Traffic Analytics — GA4 setup (kaun, kahan se, kitne)
GitHub Pages par built-in analytics nahi hai; GA4 free + standard hai.
1. analytics.google.com → Google account (artvisioncnc@gmail.com) se login
2. **Start measuring** → Account: `Art Vision Studio` → Property: `ArtVision DesiMuseum` →
   Timezone **India**, Currency **INR** → business goals me "Drive online sales"
3. **Data stream → Web** → URL: `https://rjsarkar83.github.io/ArtVision_DesiMuseum` → Create
4. **Measurement ID** milega: `G-XXXXXXXXXX` jaisa
5. Repo me `index.html` edit karein (GitHub par pencil icon) → dono
   `G-XXXXXXXXXX` ko apne ID se replace → Commit. 1-2 min me live.
6. Data dekhna: analytics.google.com → **Realtime** (turant), **Reports →
   Acquisition** (kahan se: google/instagram/pinterest/whatsapp/direct),
   **Audience → Geography** (desh-shehar). Mobile: "Google Analytics" app.
- WhatsApp order click = `whatsapp_order_click` event (code me laga hai) →
  Admin → Events me dikhega: kitne log order ke liye WhatsApp khole.
- Instagram bio / Pinterest link me UTM lagayein taaki source pakda jaye:
  `https://rjsarkar83.github.io/ArtVision_DesiMuseum/?utm_source=instagram&utm_medium=social`
- Optional: Microsoft Clarity (free) → heatmap + session recording.
