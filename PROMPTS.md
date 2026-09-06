# PROMPTS.md — 529 Coming-Soon Artworks (Art Vision Studio)

Gallery me 705 tiles hain: **176 live** + **529 "Coming soon"**.
Jaise hi koi image apne **exact filename** se `desi-deck/` folder me save karoge, uska tile **automatically** live ho jayega — koi code change nahi karna.

## Generate kaise karein
- Kisi bhi AI image tool (ya Arena agent) me neeche ka prompt paste karo → 1:1 square image banao.
- Arena agent se: bolo **"PROMPTS.md ke entry N se M generate karo"** (limit 10 images/turn, ~53 turns me sab).
- Compress karke exact naam se save karo:

```python
from PIL import Image
im = Image.open('generated.png').convert('RGB')
im.thumbnail((1200, 1200))
im.save('art_tribe_gond.jpg', quality=82, progressive=True, optimize=True)  # exact filename
```

> **Note:** agar filename typo hua to tile "Coming soon" hi rahega — naam bilkul copy-paste karo.

---

## Part A — 705 Tribes Portrait Series (257 images)

### A1. `art_tribe_great_andamanese.jpg` — Great Andamanese (Andaman & Nicobar)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Great Andamanese people of Andaman & Nicobar: shell ornaments, dugout canoe and coral-sea motifs. Rendered in flowing ocean-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A2. `art_tribe_onge.jpg` — Onge (Andaman & Nicobar)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Onge people of Andaman & Nicobar: ocean, coral reef and forest motifs, loom weaving scene. Rendered in flowing ocean-line folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A3. `art_tribe_jarawa.jpg` — Jarawa (Andaman & Nicobar)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Jarawa people of Andaman & Nicobar: ochre body-paint patterns and forest motifs. Rendered in flowing ocean-line folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A4. `art_tribe_sentinelese.jpg` — Sentinelese (Andaman & Nicobar)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sentinelese people of Andaman & Nicobar: reef-lagoon and forest silhouette motifs. Rendered in flowing ocean-line folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A5. `art_tribe_shompen.jpg` — Shompen (Andaman & Nicobar)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Shompen people of Andaman & Nicobar: ocean, coral reef and forest motifs, market day scene. Rendered in flowing ocean-line folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A6. `art_tribe_nicobarese.jpg` — Nicobarese (Andaman & Nicobar)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Nicobarese people of Andaman & Nicobar: coconut palm, canoe and harvest-festival motifs. Rendered in flowing ocean-line folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A7. `art_tribe_nyishi.jpg` — Nyishi (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Nyishi people of Arunachal Pradesh: bamboo-cane craft and hornbill motifs. Rendered in woven-geometric tribal style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A8. `art_tribe_adi.jpg` — Adi (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Adi people of Arunachal Pradesh: longhouse and river-bridge motifs. Rendered in woven-geometric tribal style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A9. `art_tribe_galo.jpg` — Galo (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Galo people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, monsoon sowing scene. Rendered in woven-geometric tribal style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A10. `art_tribe_apatani.jpg` — Apatani (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Apatani people of Arunachal Pradesh: terraced wet-rice fields and pine-grove motifs. Rendered in woven-geometric tribal style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A11. `art_tribe_tagin.jpg` — Tagin (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tagin people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, harvest dance scene. Rendered in woven-geometric tribal style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A12. `art_tribe_idu_mishmi.jpg` — Idu Mishmi (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Idu Mishmi people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, loom weaving scene. Rendered in woven-geometric tribal style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A13. `art_tribe_miju_mishmi.jpg` — Miju Mishmi (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Miju Mishmi people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, river fishing scene. Rendered in woven-geometric tribal style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A14. `art_tribe_digaru_mishmi.jpg` — Digaru Mishmi (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Digaru Mishmi people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, drum festival scene. Rendered in woven-geometric tribal style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A15. `art_tribe_khampti.jpg` — Khampti (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Khampti people of Arunachal Pradesh: gilded stupa and rice-field motifs. Rendered in woven-geometric tribal style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A16. `art_tribe_singpho.jpg` — Singpho (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Singpho people of Arunachal Pradesh: tea-leaf and gong motifs. Rendered in woven-geometric tribal style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A17. `art_tribe_nocte.jpg` — Nocte (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Nocte people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, hill-terrace farming scene. Rendered in woven-geometric tribal style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A18. `art_tribe_wancho.jpg` — Wancho (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Wancho people of Arunachal Pradesh: wood carving and orange-grove motifs. Rendered in woven-geometric tribal style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A19. `art_tribe_tangsa.jpg` — Tangsa (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tangsa people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, monsoon sowing scene. Rendered in woven-geometric tribal style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A20. `art_tribe_tutsa.jpg` — Tutsa (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tutsa people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, firelight songs scene. Rendered in woven-geometric tribal style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A21. `art_tribe_bugun.jpg` — Bugun (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bugun people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, harvest dance scene. Rendered in woven-geometric tribal style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A22. `art_tribe_puroik_sulung.jpg` — Puroik (Sulung) (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Puroik (Sulung) people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, loom weaving scene. Rendered in woven-geometric tribal style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A23. `art_tribe_khowa.jpg` — Khowa (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Khowa people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, river fishing scene. Rendered in woven-geometric tribal style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A24. `art_tribe_miji.jpg` — Miji (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Miji people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, drum festival scene. Rendered in woven-geometric tribal style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A25. `art_tribe_sherdukpen.jpg` — Sherdukpen (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sherdukpen people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, market day scene. Rendered in woven-geometric tribal style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A26. `art_tribe_bangru_aka.jpg` — Bangru (Aka) (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bangru (Aka) people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, forest gathering scene. Rendered in woven-geometric tribal style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A27. `art_tribe_milang.jpg` — Milang (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Milang people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, hill-terrace farming scene. Rendered in woven-geometric tribal style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A28. `art_tribe_memba.jpg` — Memba (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Memba people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, bamboo craft scene. Rendered in woven-geometric tribal style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A29. `art_tribe_zakhring.jpg` — Zakhring (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Zakhring people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, monsoon sowing scene. Rendered in woven-geometric tribal style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A30. `art_tribe_kaman_meyor.jpg` — Kaman (Meyor) (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kaman (Meyor) people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, firelight songs scene. Rendered in woven-geometric tribal style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A31. `art_tribe_lisu_yobin.jpg` — Lisu (Yobin) (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lisu (Yobin) people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, harvest dance scene. Rendered in woven-geometric tribal style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A32. `art_tribe_padam.jpg` — Padam (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Padam people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, loom weaving scene. Rendered in woven-geometric tribal style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A33. `art_tribe_minyong.jpg` — Minyong (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Minyong people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, river fishing scene. Rendered in woven-geometric tribal style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A34. `art_tribe_boker.jpg` — Boker (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Boker people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, drum festival scene. Rendered in woven-geometric tribal style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A35. `art_tribe_pasi.jpg` — Pasi (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Pasi people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, market day scene. Rendered in woven-geometric tribal style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A36. `art_tribe_shimong.jpg` — Shimong (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Shimong people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, forest gathering scene. Rendered in woven-geometric tribal style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A37. `art_tribe_karko.jpg` — Karko (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Karko people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, hill-terrace farming scene. Rendered in woven-geometric tribal style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A38. `art_tribe_bori.jpg` — Bori (Arunachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bori people of Arunachal Pradesh: bamboo, cane weave and hornbill motifs, bamboo craft scene. Rendered in woven-geometric tribal style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A39. `art_tribe_angami.jpg` — Angami (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Angami people of Nagaland: Sekrenyi festival and terrace-field motifs. Rendered in bold woven-shawl geometry style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A40. `art_tribe_ao.jpg` — Ao (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Ao people of Nagaland: log drum and woven-shawl motifs. Rendered in bold woven-shawl geometry style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A41. `art_tribe_sumi.jpg` — Sumi (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sumi people of Nagaland: woven shawl stripe and log-drum motifs, harvest dance scene. Rendered in bold woven-shawl geometry style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A42. `art_tribe_lotha.jpg` — Lotha (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lotha people of Nagaland: woven shawl stripe and log-drum motifs, loom weaving scene. Rendered in bold woven-shawl geometry style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A43. `art_tribe_rengma.jpg` — Rengma (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Rengma people of Nagaland: woven shawl stripe and log-drum motifs, river fishing scene. Rendered in bold woven-shawl geometry style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A44. `art_tribe_konyak.jpg` — Konyak (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Konyak people of Nagaland: morung youth-house and tattoo motifs. Rendered in bold woven-shawl geometry style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A45. `art_tribe_chang.jpg` — Chang (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chang people of Nagaland: woven shawl stripe and log-drum motifs, market day scene. Rendered in bold woven-shawl geometry style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A46. `art_tribe_sangtam.jpg` — Sangtam (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sangtam people of Nagaland: woven shawl stripe and log-drum motifs, forest gathering scene. Rendered in bold woven-shawl geometry style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A47. `art_tribe_yimkhiung.jpg` — Yimkhiung (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Yimkhiung people of Nagaland: woven shawl stripe and log-drum motifs, hill-terrace farming scene. Rendered in bold woven-shawl geometry style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A48. `art_tribe_khiamniungan.jpg` — Khiamniungan (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Khiamniungan people of Nagaland: woven shawl stripe and log-drum motifs, bamboo craft scene. Rendered in bold woven-shawl geometry style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A49. `art_tribe_tikhir.jpg` — Tikhir (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tikhir people of Nagaland: woven shawl stripe and log-drum motifs, monsoon sowing scene. Rendered in bold woven-shawl geometry style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A50. `art_tribe_zeme.jpg` — Zeme (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Zeme people of Nagaland: woven shawl stripe and log-drum motifs, firelight songs scene. Rendered in bold woven-shawl geometry style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A51. `art_tribe_liangmai.jpg` — Liangmai (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Liangmai people of Nagaland: woven shawl stripe and log-drum motifs, harvest dance scene. Rendered in bold woven-shawl geometry style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A52. `art_tribe_rongmei.jpg` — Rongmei (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Rongmei people of Nagaland: woven shawl stripe and log-drum motifs, loom weaving scene. Rendered in bold woven-shawl geometry style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A53. `art_tribe_poumai.jpg` — Poumai (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Poumai people of Nagaland: woven shawl stripe and log-drum motifs, river fishing scene. Rendered in bold woven-shawl geometry style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A54. `art_tribe_maram.jpg` — Maram (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Maram people of Nagaland: woven shawl stripe and log-drum motifs, drum festival scene. Rendered in bold woven-shawl geometry style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A55. `art_tribe_mao.jpg` — Mao (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mao people of Nagaland: woven shawl stripe and log-drum motifs, market day scene. Rendered in bold woven-shawl geometry style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A56. `art_tribe_paomata.jpg` — Paomata (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Paomata people of Nagaland: woven shawl stripe and log-drum motifs, forest gathering scene. Rendered in bold woven-shawl geometry style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A57. `art_tribe_chakhesang.jpg` — Chakhesang (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chakhesang people of Nagaland: woven shawl stripe and log-drum motifs, hill-terrace farming scene. Rendered in bold woven-shawl geometry style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A58. `art_tribe_phom.jpg` — Phom (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Phom people of Nagaland: woven shawl stripe and log-drum motifs, bamboo craft scene. Rendered in bold woven-shawl geometry style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A59. `art_tribe_thangal.jpg` — Thangal (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Thangal people of Nagaland: woven shawl stripe and log-drum motifs, monsoon sowing scene. Rendered in bold woven-shawl geometry style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A60. `art_tribe_inpui.jpg` — Inpui (Nagaland)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Inpui people of Nagaland: woven shawl stripe and log-drum motifs, firelight songs scene. Rendered in bold woven-shawl geometry style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A61. `art_tribe_tangkhul.jpg` — Tangkhul (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tangkhul people of Manipur: shirui lily and hill motifs. Rendered in graceful dance-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A62. `art_tribe_thadou.jpg` — Thadou (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Thadou people of Manipur: floating lake and dance motifs, loom weaving scene. Rendered in graceful dance-line folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A63. `art_tribe_hmar.jpg` — Hmar (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Hmar people of Manipur: floating lake and dance motifs, river fishing scene. Rendered in graceful dance-line folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A64. `art_tribe_paite.jpg` — Paite (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Paite people of Manipur: floating lake and dance motifs, drum festival scene. Rendered in graceful dance-line folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A65. `art_tribe_vaiphei.jpg` — Vaiphei (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Vaiphei people of Manipur: floating lake and dance motifs, market day scene. Rendered in graceful dance-line folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A66. `art_tribe_kom.jpg` — Kom (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kom people of Manipur: floating lake and dance motifs, forest gathering scene. Rendered in graceful dance-line folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A67. `art_tribe_aimol.jpg` — Aimol (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Aimol people of Manipur: floating lake and dance motifs, hill-terrace farming scene. Rendered in graceful dance-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A68. `art_tribe_anal.jpg` — Anal (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Anal people of Manipur: floating lake and dance motifs, bamboo craft scene. Rendered in graceful dance-line folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A69. `art_tribe_maring.jpg` — Maring (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Maring people of Manipur: floating lake and dance motifs, monsoon sowing scene. Rendered in graceful dance-line folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A70. `art_tribe_monsang.jpg` — Monsang (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Monsang people of Manipur: floating lake and dance motifs, firelight songs scene. Rendered in graceful dance-line folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A71. `art_tribe_moyon.jpg` — Moyon (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Moyon people of Manipur: floating lake and dance motifs, harvest dance scene. Rendered in graceful dance-line folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A72. `art_tribe_tarao.jpg` — Tarao (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tarao people of Manipur: floating lake and dance motifs, loom weaving scene. Rendered in graceful dance-line folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A73. `art_tribe_chiru.jpg` — Chiru (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chiru people of Manipur: floating lake and dance motifs, river fishing scene. Rendered in graceful dance-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A74. `art_tribe_purum.jpg` — Purum (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Purum people of Manipur: floating lake and dance motifs, drum festival scene. Rendered in graceful dance-line folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A75. `art_tribe_koireng.jpg` — Koireng (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Koireng people of Manipur: floating lake and dance motifs, market day scene. Rendered in graceful dance-line folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A76. `art_tribe_lamkang.jpg` — Lamkang (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lamkang people of Manipur: floating lake and dance motifs, forest gathering scene. Rendered in graceful dance-line folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A77. `art_tribe_zou.jpg` — Zou (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Zou people of Manipur: floating lake and dance motifs, hill-terrace farming scene. Rendered in graceful dance-line folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A78. `art_tribe_gangte.jpg` — Gangte (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gangte people of Manipur: floating lake and dance motifs, bamboo craft scene. Rendered in graceful dance-line folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A79. `art_tribe_simte.jpg` — Simte (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Simte people of Manipur: floating lake and dance motifs, monsoon sowing scene. Rendered in graceful dance-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A80. `art_tribe_ralte.jpg` — Ralte (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Ralte people of Manipur: floating lake and dance motifs, firelight songs scene. Rendered in graceful dance-line folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A81. `art_tribe_kabui.jpg` — Kabui (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kabui people of Manipur: floating lake and dance motifs, harvest dance scene. Rendered in graceful dance-line folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A82. `art_tribe_khoibu.jpg` — Khoibu (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Khoibu people of Manipur: floating lake and dance motifs, loom weaving scene. Rendered in graceful dance-line folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A83. `art_tribe_chothe.jpg` — Chothe (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chothe people of Manipur: floating lake and dance motifs, river fishing scene. Rendered in graceful dance-line folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A84. `art_tribe_kharam.jpg` — Kharam (Manipur)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kharam people of Manipur: floating lake and dance motifs, drum festival scene. Rendered in graceful dance-line folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A85. `art_tribe_khasi.jpg` — Khasi (Meghalaya)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Khasi people of Meghalaya: living root bridges and monolith motifs. Rendered in rain-mist folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A86. `art_tribe_pnar_jaintia.jpg` — Pnar (Jaintia) (Meghalaya)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Pnar (Jaintia) people of Meghalaya: living root bridge and rain-cloud motifs, forest gathering scene. Rendered in rain-mist folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A87. `art_tribe_garo.jpg` — Garo (Meghalaya)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Garo people of Meghalaya: Wangala drum-dance motifs. Rendered in rain-mist folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A88. `art_tribe_war.jpg` — War (Meghalaya)
> Square 1:1 Indian folk-art canvas masterpiece honouring the War people of Meghalaya: living root bridge and rain-cloud motifs, bamboo craft scene. Rendered in rain-mist folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A89. `art_tribe_bhoi.jpg` — Bhoi (Meghalaya)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhoi people of Meghalaya: living root bridge and rain-cloud motifs, monsoon sowing scene. Rendered in rain-mist folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A90. `art_tribe_lyngngam.jpg` — Lyngngam (Meghalaya)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lyngngam people of Meghalaya: living root bridge and rain-cloud motifs, firelight songs scene. Rendered in rain-mist folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A91. `art_tribe_tripuri.jpg` — Tripuri (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tripuri people of Tripura: bamboo grove and hill motifs, harvest dance scene. Rendered in bamboo-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A92. `art_tribe_reang_bru.jpg` — Reang (Bru) (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Reang (Bru) people of Tripura: bamboo grove and hill motifs, loom weaving scene. Rendered in bamboo-line folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A93. `art_tribe_jamatia.jpg` — Jamatia (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Jamatia people of Tripura: bamboo grove and hill motifs, river fishing scene. Rendered in bamboo-line folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A94. `art_tribe_noatia.jpg` — Noatia (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Noatia people of Tripura: bamboo grove and hill motifs, drum festival scene. Rendered in bamboo-line folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A95. `art_tribe_halam.jpg` — Halam (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Halam people of Tripura: bamboo grove and hill motifs, market day scene. Rendered in bamboo-line folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A96. `art_tribe_uchai.jpg` — Uchai (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Uchai people of Tripura: bamboo grove and hill motifs, forest gathering scene. Rendered in bamboo-line folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A97. `art_tribe_darlong.jpg` — Darlong (Tripura)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Darlong people of Tripura: bamboo grove and hill motifs, hill-terrace farming scene. Rendered in bamboo-line folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A98. `art_tribe_mizo.jpg` — Mizo (Mizoram)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mizo people of Mizoram: bamboo, hill-terrace and harvest motifs. Rendered in hill-terrace folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A99. `art_tribe_mara_lakher.jpg` — Mara (Lakher) (Mizoram)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mara (Lakher) people of Mizoram: bamboo, blossom and hill-terrace motifs, monsoon sowing scene. Rendered in hill-terrace folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A100. `art_tribe_chakma.jpg` — Chakma (Mizoram)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chakma people of Mizoram: bamboo, blossom and hill-terrace motifs, firelight songs scene. Rendered in hill-terrace folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A101. `art_tribe_bodo.jpg` — Bodo (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bodo people of Assam: Bagurumba dance and Dokhona weave motifs. Rendered in red-river folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A102. `art_tribe_mishing.jpg` — Mishing (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mishing people of Assam: red river, weaving and forest motifs, loom weaving scene. Rendered in red-river folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A103. `art_tribe_karbi.jpg` — Karbi (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Karbi people of Assam: red river, weaving and forest motifs, river fishing scene. Rendered in red-river folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A104. `art_tribe_rabha.jpg` — Rabha (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Rabha people of Assam: red river, weaving and forest motifs, drum festival scene. Rendered in red-river folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A105. `art_tribe_tiwa.jpg` — Tiwa (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tiwa people of Assam: red river, weaving and forest motifs, market day scene. Rendered in red-river folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A106. `art_tribe_deori.jpg` — Deori (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Deori people of Assam: red river, weaving and forest motifs, forest gathering scene. Rendered in red-river folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A107. `art_tribe_sonowal_kachari.jpg` — Sonowal Kachari (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sonowal Kachari people of Assam: red river, weaving and forest motifs, hill-terrace farming scene. Rendered in red-river folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A108. `art_tribe_thengal_kachari.jpg` — Thengal Kachari (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Thengal Kachari people of Assam: red river, weaving and forest motifs, bamboo craft scene. Rendered in red-river folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A109. `art_tribe_dimasa.jpg` — Dimasa (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dimasa people of Assam: red river, weaving and forest motifs, monsoon sowing scene. Rendered in red-river folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A110. `art_tribe_moran.jpg` — Moran (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Moran people of Assam: red river, weaving and forest motifs, firelight songs scene. Rendered in red-river folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A111. `art_tribe_tai_ahom.jpg` — Tai Ahom (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tai Ahom people of Assam: red river, weaving and forest motifs, harvest dance scene. Rendered in red-river folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A112. `art_tribe_tai_phake.jpg` — Tai Phake (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tai Phake people of Assam: red river, weaving and forest motifs, loom weaving scene. Rendered in red-river folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A113. `art_tribe_tai_turung.jpg` — Tai Turung (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tai Turung people of Assam: red river, weaving and forest motifs, river fishing scene. Rendered in red-river folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A114. `art_tribe_tai_aiton.jpg` — Tai Aiton (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tai Aiton people of Assam: red river, weaving and forest motifs, drum festival scene. Rendered in red-river folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A115. `art_tribe_tai_khamyang.jpg` — Tai Khamyang (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tai Khamyang people of Assam: red river, weaving and forest motifs, market day scene. Rendered in red-river folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A116. `art_tribe_hajong.jpg` — Hajong (Assam)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Hajong people of Assam: red river, weaving and forest motifs, forest gathering scene. Rendered in red-river folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A117. `art_tribe_lepcha.jpg` — Lepcha (Sikkim)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lepcha people of Sikkim: Himalayan orchid and loom motifs. Rendered in Himalayan thangka-line style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A118. `art_tribe_bhutia.jpg` — Bhutia (Sikkim)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhutia people of Sikkim: orchid, prayer flag and mountain motifs, bamboo craft scene. Rendered in Himalayan thangka-line style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A119. `art_tribe_limboo.jpg` — Limboo (Sikkim)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Limboo people of Sikkim: orchid, prayer flag and mountain motifs, monsoon sowing scene. Rendered in Himalayan thangka-line style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A120. `art_tribe_tamang.jpg` — Tamang (Sikkim)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tamang people of Sikkim: orchid, prayer flag and mountain motifs, firelight songs scene. Rendered in Himalayan thangka-line style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A121. `art_tribe_bhumij.jpg` — Bhumij (West Bengal)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhumij people of West Bengal: river delta and folk-scroll motifs, harvest dance scene. Rendered in Kalighat pat bold-line style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A122. `art_tribe_kora.jpg` — Kora (West Bengal)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kora people of West Bengal: river delta and folk-scroll motifs, loom weaving scene. Rendered in Kalighat pat bold-line style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A123. `art_tribe_lodha.jpg` — Lodha (West Bengal)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lodha people of West Bengal: river delta and folk-scroll motifs, river fishing scene. Rendered in Kalighat pat bold-line style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A124. `art_tribe_mahali.jpg` — Mahali (West Bengal)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mahali people of West Bengal: river delta and folk-scroll motifs, drum festival scene. Rendered in Kalighat pat bold-line style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A125. `art_tribe_toto.jpg` — Toto (West Bengal)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Toto people of West Bengal: river delta and folk-scroll motifs, market day scene. Rendered in Kalighat pat bold-line style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A126. `art_tribe_santhal.jpg` — Santhal (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Santhal people of Jharkhand: sal forest, jadopatia scroll and harvest motifs. Rendered in Jadopatia scroll style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A127. `art_tribe_munda.jpg` — Munda (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Munda people of Jharkhand: sal forest and scroll motifs, hill-terrace farming scene. Rendered in Jadopatia scroll style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A128. `art_tribe_ho.jpg` — Ho (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Ho people of Jharkhand: sal forest and scroll motifs, bamboo craft scene. Rendered in Jadopatia scroll style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A129. `art_tribe_oraon_kurukh.jpg` — Oraon (Kurukh) (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Oraon (Kurukh) people of Jharkhand: sal forest and scroll motifs, monsoon sowing scene. Rendered in Jadopatia scroll style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A130. `art_tribe_kharia.jpg` — Kharia (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kharia people of Jharkhand: sal forest and scroll motifs, firelight songs scene. Rendered in Jadopatia scroll style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A131. `art_tribe_asur.jpg` — Asur (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Asur people of Jharkhand: traditional iron-smelting motifs. Rendered in Jadopatia scroll style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A132. `art_tribe_birhor.jpg` — Birhor (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Birhor people of Jharkhand: rope-craft and forest-canopy motifs. Rendered in Jadopatia scroll style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A133. `art_tribe_sauria_paharia.jpg` — Sauria Paharia (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sauria Paharia people of Jharkhand: sal forest and scroll motifs, river fishing scene. Rendered in Jadopatia scroll style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A134. `art_tribe_mal_paharia.jpg` — Mal Paharia (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mal Paharia people of Jharkhand: sal forest and scroll motifs, drum festival scene. Rendered in Jadopatia scroll style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A135. `art_tribe_korwa.jpg` — Korwa (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Korwa people of Jharkhand: sal forest and scroll motifs, market day scene. Rendered in Jadopatia scroll style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A136. `art_tribe_chero.jpg` — Chero (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chero people of Jharkhand: sal forest and scroll motifs, forest gathering scene. Rendered in Jadopatia scroll style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A137. `art_tribe_bediya.jpg` — Bediya (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bediya people of Jharkhand: sal forest and scroll motifs, hill-terrace farming scene. Rendered in Jadopatia scroll style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A138. `art_tribe_parhaiya.jpg` — Parhaiya (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Parhaiya people of Jharkhand: sal forest and scroll motifs, bamboo craft scene. Rendered in Jadopatia scroll style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A139. `art_tribe_chik_baraik.jpg` — Chik Baraik (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chik Baraik people of Jharkhand: sal forest and scroll motifs, monsoon sowing scene. Rendered in Jadopatia scroll style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A140. `art_tribe_gorait.jpg` — Gorait (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gorait people of Jharkhand: earthen-potter motifs. Rendered in Jadopatia scroll style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A141. `art_tribe_turi.jpg` — Turi (Jharkhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Turi people of Jharkhand: sal forest and scroll motifs, harvest dance scene. Rendered in Jadopatia scroll style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A142. `art_tribe_kandha_khond.jpg` — Kandha (Khond) (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kandha (Khond) people of Odisha: turmeric valley and forest motifs. Rendered in Saura idital wall style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A143. `art_tribe_dongria_kondh.jpg` — Dongria Kondh (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dongria Kondh people of Odisha: sacred hill motifs. Rendered in Saura idital wall style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A144. `art_tribe_kutia_kondh.jpg` — Kutia Kondh (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kutia Kondh people of Odisha: temple wheel, sea and weave motifs, drum festival scene. Rendered in Saura idital wall style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A145. `art_tribe_bondo.jpg` — Bondo (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bondo people of Odisha: bead-and-brass ornament motifs. Rendered in Saura idital wall style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A146. `art_tribe_paraja.jpg` — Paraja (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Paraja people of Odisha: temple wheel, sea and weave motifs, forest gathering scene. Rendered in Saura idital wall style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A147. `art_tribe_gadaba.jpg` — Gadaba (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gadaba people of Odisha: Kerang dance motifs. Rendered in Saura idital wall style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A148. `art_tribe_dhurua.jpg` — Dhurua (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dhurua people of Odisha: temple wheel, sea and weave motifs, bamboo craft scene. Rendered in Saura idital wall style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A149. `art_tribe_didayi.jpg` — Didayi (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Didayi people of Odisha: temple wheel, sea and weave motifs, monsoon sowing scene. Rendered in Saura idital wall style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A150. `art_tribe_koya.jpg` — Koya (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Koya people of Odisha: temple wheel, sea and weave motifs, firelight songs scene. Rendered in Saura idital wall style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A151. `art_tribe_juang.jpg` — Juang (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Juang people of Odisha: temple wheel, sea and weave motifs, harvest dance scene. Rendered in Saura idital wall style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A152. `art_tribe_saura.jpg` — Saura (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Saura people of Odisha: Idital wall-painting motifs. Rendered in Saura idital wall style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A153. `art_tribe_bhatra.jpg` — Bhatra (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhatra people of Odisha: temple wheel, sea and weave motifs, river fishing scene. Rendered in Saura idital wall style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A154. `art_tribe_kolha.jpg` — Kolha (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kolha people of Odisha: temple wheel, sea and weave motifs, drum festival scene. Rendered in Saura idital wall style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A155. `art_tribe_matia.jpg` — Matia (Odisha)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Matia people of Odisha: temple wheel, sea and weave motifs, market day scene. Rendered in Saura idital wall style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A156. `art_tribe_baiga.jpg` — Baiga (Chhattisgarh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Baiga people of Chhattisgarh: tattoo art and forest motifs. Rendered in Gond digna-dot style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A157. `art_tribe_kamar.jpg` — Kamar (Chhattisgarh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kamar people of Chhattisgarh: sal forest and bell-metal motifs, hill-terrace farming scene. Rendered in Gond digna-dot style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A158. `art_tribe_kanwar.jpg` — Kanwar (Chhattisgarh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kanwar people of Chhattisgarh: sal forest and bell-metal motifs, bamboo craft scene. Rendered in Gond digna-dot style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A159. `art_tribe_halba.jpg` — Halba (Chhattisgarh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Halba people of Chhattisgarh: sal forest and bell-metal motifs, monsoon sowing scene. Rendered in Gond digna-dot style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A160. `art_tribe_dhruwa.jpg` — Dhruwa (Chhattisgarh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dhruwa people of Chhattisgarh: sal forest and bell-metal motifs, firelight songs scene. Rendered in Gond digna-dot style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A161. `art_tribe_gond.jpg` — Gond (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gond people of Madhya Pradesh: Digna dot-pattern forest motifs. Rendered in Gond dot-pattern style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A162. `art_tribe_bhil.jpg` — Bhil (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhil people of Madhya Pradesh: Pithora ritual-horse motifs. Rendered in Gond dot-pattern style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A163. `art_tribe_bhilala.jpg` — Bhilala (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhilala people of Madhya Pradesh: forest, peacock and dot-pattern motifs, river fishing scene. Rendered in Gond dot-pattern style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A164. `art_tribe_barela.jpg` — Barela (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Barela people of Madhya Pradesh: forest, peacock and dot-pattern motifs, drum festival scene. Rendered in Gond dot-pattern style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A165. `art_tribe_patelia.jpg` — Patelia (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Patelia people of Madhya Pradesh: forest, peacock and dot-pattern motifs, market day scene. Rendered in Gond dot-pattern style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A166. `art_tribe_korku.jpg` — Korku (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Korku people of Madhya Pradesh: forest, peacock and dot-pattern motifs, forest gathering scene. Rendered in Gond dot-pattern style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A167. `art_tribe_sahariya.jpg` — Sahariya (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sahariya people of Madhya Pradesh: forest, peacock and dot-pattern motifs, hill-terrace farming scene. Rendered in Gond dot-pattern style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A168. `art_tribe_kol.jpg` — Kol (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kol people of Madhya Pradesh: forest, peacock and dot-pattern motifs, bamboo craft scene. Rendered in Gond dot-pattern style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A169. `art_tribe_bharia.jpg` — Bharia (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bharia people of Madhya Pradesh: forest, peacock and dot-pattern motifs, monsoon sowing scene. Rendered in Gond dot-pattern style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A170. `art_tribe_nihali.jpg` — Nihali (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Nihali people of Madhya Pradesh: forest, peacock and dot-pattern motifs, firelight songs scene. Rendered in Gond dot-pattern style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A171. `art_tribe_pardhan.jpg` — Pardhan (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Pardhan people of Madhya Pradesh: Bana fiddle bard motifs. Rendered in Gond dot-pattern style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A172. `art_tribe_agariya.jpg` — Agariya (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Agariya people of Madhya Pradesh: forest, peacock and dot-pattern motifs, loom weaving scene. Rendered in Gond dot-pattern style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A173. `art_tribe_bhunjia.jpg` — Bhunjia (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bhunjia people of Madhya Pradesh: forest, peacock and dot-pattern motifs, river fishing scene. Rendered in Gond dot-pattern style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A174. `art_tribe_pawra.jpg` — Pawra (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Pawra people of Madhya Pradesh: forest, peacock and dot-pattern motifs, drum festival scene. Rendered in Gond dot-pattern style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A175. `art_tribe_rajgond.jpg` — Rajgond (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Rajgond people of Madhya Pradesh: forest, peacock and dot-pattern motifs, market day scene. Rendered in Gond dot-pattern style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A176. `art_tribe_dhur_gond.jpg` — Dhur Gond (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dhur Gond people of Madhya Pradesh: forest, peacock and dot-pattern motifs, forest gathering scene. Rendered in Gond dot-pattern style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A177. `art_tribe_muria.jpg` — Muria (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Muria people of Madhya Pradesh: Ghotul youth-house motifs. Rendered in Gond dot-pattern style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A178. `art_tribe_madiya.jpg` — Madiya (Madhya Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Madiya people of Madhya Pradesh: forest, peacock and dot-pattern motifs, bamboo craft scene. Rendered in Gond dot-pattern style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A179. `art_tribe_rathwa.jpg` — Rathwa (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Rathwa people of Gujarat: Pithora painting motifs. Rendered in mirror-work folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A180. `art_tribe_naikda.jpg` — Naikda (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Naikda people of Gujarat: mirror work and bandhani dot motifs, firelight songs scene. Rendered in mirror-work folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A181. `art_tribe_chodhara.jpg` — Chodhara (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chodhara people of Gujarat: mirror work and bandhani dot motifs, harvest dance scene. Rendered in mirror-work folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A182. `art_tribe_dhodia.jpg` — Dhodia (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dhodia people of Gujarat: mirror work and bandhani dot motifs, loom weaving scene. Rendered in mirror-work folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A183. `art_tribe_gamit.jpg` — Gamit (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gamit people of Gujarat: mirror work and bandhani dot motifs, river fishing scene. Rendered in mirror-work folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A184. `art_tribe_dubla.jpg` — Dubla (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dubla people of Gujarat: mirror work and bandhani dot motifs, drum festival scene. Rendered in mirror-work folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A185. `art_tribe_halpati.jpg` — Halpati (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Halpati people of Gujarat: mirror work and bandhani dot motifs, market day scene. Rendered in mirror-work folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A186. `art_tribe_kotwalia.jpg` — Kotwalia (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kotwalia people of Gujarat: mirror work and bandhani dot motifs, forest gathering scene. Rendered in mirror-work folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A187. `art_tribe_barda.jpg` — Barda (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Barda people of Gujarat: mirror work and bandhani dot motifs, hill-terrace farming scene. Rendered in mirror-work folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A188. `art_tribe_siddi.jpg` — Siddi (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Siddi people of Gujarat: Dhamal drum-dance motifs. Rendered in mirror-work folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A189. `art_tribe_vaghri.jpg` — Vaghri (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Vaghri people of Gujarat: mirror work and bandhani dot motifs, monsoon sowing scene. Rendered in mirror-work folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A190. `art_tribe_vasava.jpg` — Vasava (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Vasava people of Gujarat: mirror work and bandhani dot motifs, firelight songs scene. Rendered in mirror-work folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A191. `art_tribe_tadvi.jpg` — Tadvi (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tadvi people of Gujarat: mirror work and bandhani dot motifs, harvest dance scene. Rendered in mirror-work folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A192. `art_tribe_talavia.jpg` — Talavia (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Talavia people of Gujarat: mirror work and bandhani dot motifs, loom weaving scene. Rendered in mirror-work folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A193. `art_tribe_dhanka.jpg` — Dhanka (Gujarat)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Dhanka people of Gujarat: mirror work and bandhani dot motifs, river fishing scene. Rendered in mirror-work folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A194. `art_tribe_mina_meena.jpg` — Mina (Meena) (Rajasthan)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mina (Meena) people of Rajasthan: desert dune, camel and block-print motifs, drum festival scene. Rendered in miniature folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A195. `art_tribe_kathodi.jpg` — Kathodi (Rajasthan)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kathodi people of Rajasthan: desert dune, camel and block-print motifs, market day scene. Rendered in miniature folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A196. `art_tribe_garasia.jpg` — Garasia (Rajasthan)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Garasia people of Rajasthan: desert dune, camel and block-print motifs, forest gathering scene. Rendered in miniature folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A197. `art_tribe_damor.jpg` — Damor (Rajasthan)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Damor people of Rajasthan: desert dune, camel and block-print motifs, hill-terrace farming scene. Rendered in miniature folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A198. `art_tribe_sansi_sansiya.jpg` — Sansi (Sansiya) (Rajasthan)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Sansi (Sansiya) people of Rajasthan: desert dune, camel and block-print motifs, bamboo craft scene. Rendered in miniature folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A199. `art_tribe_kalbelia.jpg` — Kalbelia (Rajasthan)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kalbelia people of Rajasthan: snake-charm dance motifs. Rendered in miniature folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A200. `art_tribe_warli.jpg` — Warli (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Warli people of Maharashtra: white-on-ochre wedding-canvas motifs. Rendered in Warli white-silhouette style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A201. `art_tribe_katkari.jpg` — Katkari (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Katkari people of Maharashtra: Sahyadri hills and dance-circle motifs, harvest dance scene. Rendered in Warli white-silhouette style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A202. `art_tribe_koli_mahadev.jpg` — Koli Mahadev (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Koli Mahadev people of Maharashtra: Sahyadri hills and dance-circle motifs, loom weaving scene. Rendered in Warli white-silhouette style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A203. `art_tribe_thakur.jpg` — Thakur (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Thakur people of Maharashtra: Sahyadri hills and dance-circle motifs, river fishing scene. Rendered in Warli white-silhouette style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A204. `art_tribe_pardhi.jpg` — Pardhi (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Pardhi people of Maharashtra: Sahyadri hills and dance-circle motifs, drum festival scene. Rendered in Warli white-silhouette style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A205. `art_tribe_kokna.jpg` — Kokna (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kokna people of Maharashtra: Sahyadri hills and dance-circle motifs, market day scene. Rendered in Warli white-silhouette style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A206. `art_tribe_kaikadi.jpg` — Kaikadi (Maharashtra)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kaikadi people of Maharashtra: Sahyadri hills and dance-circle motifs, forest gathering scene. Rendered in Warli white-silhouette style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A207. `art_tribe_gaddi.jpg` — Gaddi (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gaddi people of Himachal Pradesh: Dhankut shepherd motifs. Rendered in Pahari painting style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A208. `art_tribe_kinnaura.jpg` — Kinnaura (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kinnaura people of Himachal Pradesh: pine slope and orchard motifs, bamboo craft scene. Rendered in Pahari painting style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A209. `art_tribe_lahaula.jpg` — Lahaula (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Lahaula people of Himachal Pradesh: pine slope and orchard motifs, monsoon sowing scene. Rendered in Pahari painting style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A210. `art_tribe_swangla.jpg` — Swangla (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Swangla people of Himachal Pradesh: pine slope and orchard motifs, firelight songs scene. Rendered in Pahari painting style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A211. `art_tribe_pangwala.jpg` — Pangwala (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Pangwala people of Himachal Pradesh: pine slope and orchard motifs, harvest dance scene. Rendered in Pahari painting style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A212. `art_tribe_hatti.jpg` — Hatti (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Hatti people of Himachal Pradesh: pine slope and orchard motifs, loom weaving scene. Rendered in Pahari painting style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A213. `art_tribe_gujjar_bakarwal.jpg` — Gujjar-Bakarwal (Himachal Pradesh)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Gujjar-Bakarwal people of Himachal Pradesh: mountain-migration motifs. Rendered in Pahari painting style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A214. `art_tribe_tharu.jpg` — Tharu (Uttarakhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Tharu people of Uttarakhand: tattoo art and grass-house motifs. Rendered in Aipan line style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A215. `art_tribe_raji.jpg` — Raji (Uttarakhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Raji people of Uttarakhand: Himalayan peak and river motifs, market day scene. Rendered in Aipan line style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A216. `art_tribe_buksa.jpg` — Buksa (Uttarakhand)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Buksa people of Uttarakhand: Himalayan peak and river motifs, forest gathering scene. Rendered in Aipan line style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A217. `art_tribe_chenchu.jpg` — Chenchu (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Chenchu people of Andhra Pradesh & Telangana: Nallamala forest motifs. Rendered in Cheriyal scroll style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A218. `art_tribe_konda_reddi.jpg` — Konda Reddi (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Konda Reddi people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, bamboo craft scene. Rendered in Cheriyal scroll style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A219. `art_tribe_konda_savara.jpg` — Konda Savara (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Konda Savara people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, monsoon sowing scene. Rendered in Cheriyal scroll style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A220. `art_tribe_kolam.jpg` — Kolam (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kolam people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, firelight songs scene. Rendered in Cheriyal scroll style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A221. `art_tribe_naikpod.jpg` — Naikpod (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Naikpod people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, harvest dance scene. Rendered in Cheriyal scroll style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A222. `art_tribe_thoti.jpg` — Thoti (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Thoti people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, loom weaving scene. Rendered in Cheriyal scroll style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A223. `art_tribe_andh.jpg` — Andh (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Andh people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, river fishing scene. Rendered in Cheriyal scroll style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A224. `art_tribe_valmiki.jpg` — Valmiki (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Valmiki people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, drum festival scene. Rendered in Cheriyal scroll style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A225. `art_tribe_yerukala.jpg` — Yerukala (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Yerukala people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, market day scene. Rendered in Cheriyal scroll style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A226. `art_tribe_bagata.jpg` — Bagata (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Bagata people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, forest gathering scene. Rendered in Cheriyal scroll style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A227. `art_tribe_jatapu.jpg` — Jatapu (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Jatapu people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, hill-terrace farming scene. Rendered in Cheriyal scroll style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A228. `art_tribe_koya_godavari.jpg` — Koya (Godavari) (Andhra Pradesh & Telangana)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Koya (Godavari) people of Andhra Pradesh & Telangana: plateau, millet field and scroll motifs, bamboo craft scene. Rendered in Cheriyal scroll style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A229. `art_tribe_soliga.jpg` — Soliga (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Soliga people of Karnataka: Biligiri hills and wild-honey motifs. Rendered in Kalamkari pen style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A230. `art_tribe_jenu_kuruba.jpg` — Jenu Kuruba (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Jenu Kuruba people of Karnataka: western ghats and bison motifs, firelight songs scene. Rendered in Kalamkari pen style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A231. `art_tribe_hakki_pikki.jpg` — Hakki Pikki (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Hakki Pikki people of Karnataka: western ghats and bison motifs, harvest dance scene. Rendered in Kalamkari pen style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A232. `art_tribe_koraga.jpg` — Koraga (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Koraga people of Karnataka: western ghats and bison motifs, loom weaving scene. Rendered in Kalamkari pen style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A233. `art_tribe_kadu_kuruba.jpg` — Kadu Kuruba (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kadu Kuruba people of Karnataka: western ghats and bison motifs, river fishing scene. Rendered in Kalamkari pen style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A234. `art_tribe_betta_kuruba.jpg` — Betta Kuruba (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Betta Kuruba people of Karnataka: western ghats and bison motifs, drum festival scene. Rendered in Kalamkari pen style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A235. `art_tribe_naika.jpg` — Naika (Karnataka)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Naika people of Karnataka: western ghats and bison motifs, market day scene. Rendered in Kalamkari pen style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A236. `art_tribe_irula.jpg` — Irula (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Irula people of Kerala: backwater, coconut palm and mask motifs, forest gathering scene. Rendered in Theyyam-red folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A237. `art_tribe_paniyan.jpg` — Paniyan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Paniyan people of Kerala: backwater, coconut palm and mask motifs, hill-terrace farming scene. Rendered in Theyyam-red folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A238. `art_tribe_kurichiya.jpg` — Kurichiya (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kurichiya people of Kerala: bamboo-bow and paddy motifs. Rendered in Theyyam-red folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A239. `art_tribe_kattunayakan.jpg` — Kattunayakan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kattunayakan people of Kerala: backwater, coconut palm and mask motifs, monsoon sowing scene. Rendered in Theyyam-red folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A240. `art_tribe_cholanaikkan.jpg` — Cholanaikkan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Cholanaikkan people of Kerala: backwater, coconut palm and mask motifs, firelight songs scene. Rendered in Theyyam-red folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A241. `art_tribe_malapandaram.jpg` — Malapandaram (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Malapandaram people of Kerala: backwater, coconut palm and mask motifs, harvest dance scene. Rendered in Theyyam-red folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A242. `art_tribe_mala_arayan.jpg` — Mala Arayan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mala Arayan people of Kerala: backwater, coconut palm and mask motifs, loom weaving scene. Rendered in Theyyam-red folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A243. `art_tribe_kani_kanikaran.jpg` — Kani (Kanikaran) (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kani (Kanikaran) people of Kerala: backwater, coconut palm and mask motifs, river fishing scene. Rendered in Theyyam-red folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A244. `art_tribe_malavedan.jpg` — Malavedan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Malavedan people of Kerala: backwater, coconut palm and mask motifs, drum festival scene. Rendered in Theyyam-red folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A245. `art_tribe_urali.jpg` — Urali (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Urali people of Kerala: backwater, coconut palm and mask motifs, market day scene. Rendered in Theyyam-red folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A246. `art_tribe_mannan.jpg` — Mannan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mannan people of Kerala: backwater, coconut palm and mask motifs, forest gathering scene. Rendered in Theyyam-red folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A247. `art_tribe_muthuvan.jpg` — Muthuvan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Muthuvan people of Kerala: backwater, coconut palm and mask motifs, hill-terrace farming scene. Rendered in Theyyam-red folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A248. `art_tribe_mullu_kurumba.jpg` — Mullu Kurumba (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mullu Kurumba people of Kerala: backwater, coconut palm and mask motifs, bamboo craft scene. Rendered in Theyyam-red folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A249. `art_tribe_mala_pantaram.jpg` — Mala Pantaram (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mala Pantaram people of Kerala: backwater, coconut palm and mask motifs, monsoon sowing scene. Rendered in Theyyam-red folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A250. `art_tribe_eravallan.jpg` — Eravallan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Eravallan people of Kerala: backwater, coconut palm and mask motifs, firelight songs scene. Rendered in Theyyam-red folk style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A251. `art_tribe_malayan.jpg` — Malayan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Malayan people of Kerala: backwater, coconut palm and mask motifs, harvest dance scene. Rendered in Theyyam-red folk style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A252. `art_tribe_aranadan.jpg` — Aranadan (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Aranadan people of Kerala: backwater, coconut palm and mask motifs, loom weaving scene. Rendered in Theyyam-red folk style, palette of deep maroon, cream & copper on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A253. `art_tribe_kadar.jpg` — Kadar (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kadar people of Kerala: backwater, coconut palm and mask motifs, river fishing scene. Rendered in Theyyam-red folk style, palette of vermillion, ochre, teal & charcoal on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A254. `art_tribe_malasar.jpg` — Malasar (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Malasar people of Kerala: backwater, coconut palm and mask motifs, drum festival scene. Rendered in Theyyam-red folk style, palette of indigo, mustard & rust on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A255. `art_tribe_mudugar.jpg` — Mudugar (Kerala)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Mudugar people of Kerala: backwater, coconut palm and mask motifs, market day scene. Rendered in Theyyam-red folk style, palette of peacock teal, magenta & gold on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A256. `art_tribe_toda.jpg` — Toda (Tamil Nadu)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Toda people of Tamil Nadu: buffalo, puff-sleeve embroidery and hill motifs. Rendered in temple-fresco style, palette of earth-red, ivory & lamp-black on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### A257. `art_tribe_kota.jpg` — Kota (Tamil Nadu)
> Square 1:1 Indian folk-art canvas masterpiece honouring the Kota people of Tamil Nadu: gopuram, kolam and bazaar motifs, hill-terrace farming scene. Rendered in temple-fresco style, palette of jade green, saffron & plum on a warm ivory ground, fine line detail, subtle metallic-gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.


## Part B — Masterpiece Expansion Series (272 images)

### B1. `art_wallpaper_udaipur_palaces.jpg` — Udaipur Palaces
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Udaipur palaces: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B2. `art_wallpaper_jodhpur_blue_city.jpg` — Jodhpur Blue City
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Jodhpur blue city: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B3. `art_wallpaper_jaisalmer_golden_fort.jpg` — Jaisalmer Golden Fort
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Jaisalmer golden fort: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B4. `art_wallpaper_bundi_murals.jpg` — Bundi Murals
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Bundi murals: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B5. `art_wallpaper_pushkar_lake_town.jpg` — Pushkar Lake Town
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Pushkar lake town: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B6. `art_wallpaper_bikaner_havelis.jpg` — Bikaner Havelis
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Bikaner havelis: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B7. `art_wallpaper_puri_temple_town.jpg` — Puri Temple Town
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Puri temple town: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B8. `art_wallpaper_bhubaneswar_temples.jpg` — Bhubaneswar Temples
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Bhubaneswar temples: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B9. `art_wallpaper_leh_monastery_valley.jpg` — Leh Monastery Valley
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Leh monastery valley: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B10. `art_wallpaper_amritsar_golden_pool.jpg` — Amritsar Golden Pool
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Amritsar golden pool: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B11. `art_wallpaper_shimla_cedar_hills.jpg` — Shimla Cedar Hills
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Shimla cedar hills: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B12. `art_wallpaper_darjeeling_tea_hills.jpg` — Darjeeling Tea Hills
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Darjeeling tea hills: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B13. `art_wallpaper_gangtok_mountain_gates.jpg` — Gangtok Mountain Gates
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Gangtok mountain gates: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B14. `art_wallpaper_shillong_pine_city.jpg` — Shillong Pine City
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Shillong pine city: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B15. `art_wallpaper_aizawl_hill_town.jpg` — Aizawl Hill Town
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Aizawl hill town: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B16. `art_wallpaper_kohima_hill_terraces.jpg` — Kohima Hill Terraces
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Kohima hill terraces: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B17. `art_wallpaper_imphal_valley_blooms.jpg` — Imphal Valley Blooms
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Imphal valley blooms: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B18. `art_wallpaper_guwahati_river_city.jpg` — Guwahati River City
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Guwahati river city: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B19. `art_wallpaper_pondicherry_french_quarter.jpg` — Pondicherry French Quarter
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Pondicherry french quarter: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B20. `art_wallpaper_thanjavur_big_temple.jpg` — Thanjavur Big Temple
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Thanjavur big temple: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B21. `art_wallpaper_madurai_temple_city.jpg` — Madurai Temple City
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Madurai temple city: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B22. `art_wallpaper_chettinad_mansions.jpg` — Chettinad Mansions
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Chettinad mansions: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B23. `art_wallpaper_hampi_boulder_city.jpg` — Hampi Boulder City
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Hampi boulder city: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B24. `art_wallpaper_badami_cave_town.jpg` — Badami Cave Town
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Badami cave town: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B25. `art_wallpaper_bijapur_domes.jpg` — Bijapur Domes
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Bijapur domes: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B26. `art_wallpaper_warangal_gate_city.jpg` — Warangal Gate City
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Warangal gate city: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B27. `art_wallpaper_khajuraho_sculptures.jpg` — Khajuraho Sculptures
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Khajuraho sculptures: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B28. `art_wallpaper_orchha_riverside_forts.jpg` — Orchha Riverside Forts
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Orchha riverside forts: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B29. `art_wallpaper_chanderi_weaver_town.jpg` — Chanderi Weaver Town
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Chanderi weaver town: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B30. `art_wallpaper_maheshwar_ghats.jpg` — Maheshwar Ghats
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Maheshwar ghats: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B31. `art_wallpaper_mandu_lake_palace.jpg` — Mandu Lake Palace
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — luxury heritage wallpaper design for Mandu lake palace: seamless damask-inspired layout with regional motifs, metallic gold accents, vermillion-ochre-teal-charcoal on ivory, subtle sheen, tileable. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B32. `art_wall_bharatanatyam_dancer.jpg` — Bharatanatyam Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Bharatanatyam dancer, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B33. `art_wall_kathak_spin.jpg` — Kathak Spin
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Kathak spin, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B34. `art_wall_odissi_tribhanga.jpg` — Odissi Tribhanga
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Odissi tribhanga, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B35. `art_wall_kuchipudi_dance.jpg` — Kuchipudi Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Kuchipudi dance, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B36. `art_wall_manipuri_dance.jpg` — Manipuri Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Manipuri dance, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B37. `art_wall_mohiniyattam_pose.jpg` — Mohiniyattam Pose
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Mohiniyattam pose, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B38. `art_wall_sattriya_dance.jpg` — Sattriya Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Sattriya dance, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B39. `art_wall_bhangra_drummers.jpg` — Bhangra Drummers
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Bhangra drummers, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B40. `art_wall_giddha_circle.jpg` — Giddha Circle
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Giddha circle, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B41. `art_wall_ghoomar_swirl.jpg` — Ghoomar Swirl
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Ghoomar swirl, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B42. `art_wall_kalbelia_dance.jpg` — Kalbelia Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Kalbelia dance, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B43. `art_wall_chhau_mask_dance.jpg` — Chhau Mask Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Chhau mask dance, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B44. `art_wall_theyyam_ritual.jpg` — Theyyam Ritual
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Theyyam ritual, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B45. `art_wall_yakshagana_stage.jpg` — Yakshagana Stage
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Yakshagana stage, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B46. `art_wall_dandiya_night.jpg` — Dandiya Night
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Dandiya night, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B47. `art_wall_lavani_dancer.jpg` — Lavani Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Lavani dancer, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B48. `art_wall_bihu_dance.jpg` — Bihu Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Bihu dance, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B49. `art_wall_pongal_harvest.jpg` — Pongal Harvest
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Pongal harvest, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B50. `art_wall_onam_pookalam.jpg` — Onam Pookalam
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Onam pookalam, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B51. `art_wall_holi_colour_splash.jpg` — Holi Colour Splash
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Holi colour splash, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B52. `art_wall_diwali_lamp_rows.jpg` — Diwali Lamp Rows
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Diwali lamp rows, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B53. `art_wall_chand_raat_lanterns.jpg` — Chand Raat Lanterns
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Chand Raat lanterns, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B54. `art_wall_baisakhi_wheat_fields.jpg` — Baisakhi Wheat Fields
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Baisakhi wheat fields, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B55. `art_wall_lohri_bonfire.jpg` — Lohri Bonfire
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Lohri bonfire, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B56. `art_wall_makar_sankranti_kites_free_sky.jpg` — Makar Sankranti Kites-Free Sky
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Makar Sankranti kites-free sky, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B57. `art_wall_ugadi_neem_jaggery.jpg` — Ugadi Neem-Jaggery
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Ugadi neem-jaggery, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B58. `art_wall_chhath_river_offering.jpg` — Chhath River Offering
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Chhath river offering, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B59. `art_wall_teej_swings.jpg` — Teej Swings
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting Teej swings, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B60. `art_wall_block_printing_craft.jpg` — Block Printing Craft
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting block printing craft, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B61. `art_wall_blue_pottery_craft.jpg` — Blue Pottery Craft
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — hand-painted mural on textured lime plaster depicting blue pottery craft, natural pigment folk palette, visible brushwork, warm ivory wall ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B62. `art_folk_cheriyal_scroll_painting.jpg` — Cheriyal Scroll Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Cheriyal scroll painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B63. `art_folk_tholu_bommalata_shadow_puppets.jpg` — Tholu Bommalata Shadow Puppets
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Tholu Bommalata shadow puppets artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B64. `art_folk_rogan_cloth_art.jpg` — Rogan Cloth Art
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Rogan cloth art artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B65. `art_folk_sanjhi_paper_cut.jpg` — Sanjhi Paper Cut
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Sanjhi paper cut artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B66. `art_folk_mata_ni_pachedi_cloth.jpg` — Mata Ni Pachedi Cloth
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Mata ni Pachedi cloth artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B67. `art_folk_tikuli_lac_art.jpg` — Tikuli Lac Art
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Tikuli lac art artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B68. `art_folk_sujani_quilt_embroidery.jpg` — Sujani Quilt Embroidery
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Sujani quilt embroidery artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B69. `art_folk_sikki_grass_craft.jpg` — Sikki Grass Craft
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Sikki grass craft artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B70. `art_folk_manjusha_painting.jpg` — Manjusha Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Manjusha painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B71. `art_folk_nirmal_painting.jpg` — Nirmal Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Nirmal painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B72. `art_folk_pembarthi_brass_sheet_art.jpg` — Pembarthi Brass Sheet Art
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Pembarthi brass sheet art artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B73. `art_folk_kondapalli_wooden_toys.jpg` — Kondapalli Wooden Toys
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Kondapalli wooden toys artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B74. `art_folk_etikoppaka_lacquer_toys.jpg` — Etikoppaka Lacquer Toys
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Etikoppaka lacquer toys artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B75. `art_folk_channapatna_wooden_toys.jpg` — Channapatna Wooden Toys
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Channapatna wooden toys artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B76. `art_folk_sawantwadi_lacquer_craft.jpg` — Sawantwadi Lacquer Craft
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Sawantwadi lacquer craft artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B77. `art_folk_thanjavur_gold_leaf_painting.jpg` — Thanjavur Gold-Leaf Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Thanjavur gold-leaf painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B78. `art_folk_mysore_palace_painting.jpg` — Mysore Palace Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Mysore palace painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B79. `art_folk_kangra_pahari_painting.jpg` — Kangra Pahari Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Kangra pahari painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B80. `art_folk_basohli_painting.jpg` — Basohli Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Basohli painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B81. `art_folk_rajput_court_miniature.jpg` — Rajput Court Miniature
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Rajput court miniature artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B82. `art_folk_deccan_miniature_painting.jpg` — Deccan Miniature Painting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — authentic traditional Deccan miniature painting artwork, true materials and technique, devotional folk detail, ivory ground with earthy pigments and gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B83. `art_wild_kashmir_hangul_deer.jpg` — Kashmir Hangul Deer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of Kashmir hangul deer, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B84. `art_wild_gaur_bison.jpg` — Gaur Bison
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of gaur bison, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B85. `art_wild_swamp_deer_barasingha.jpg` — Swamp Deer Barasingha
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of swamp deer barasingha, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B86. `art_wild_blackbuck_herd.jpg` — Blackbuck Herd
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of blackbuck herd, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B87. `art_wild_chinkara.jpg` — Chinkara
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of chinkara, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B88. `art_wild_sloth_bear.jpg` — Sloth Bear
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of sloth bear, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B89. `art_wild_indian_pangolin.jpg` — Indian Pangolin
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of Indian pangolin, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B90. `art_wild_gharial.jpg` — Gharial
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of gharial, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B91. `art_wild_olive_ridley_turtle.jpg` — Olive Ridley Turtle
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of olive ridley turtle, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B92. `art_wild_hoolock_gibbon.jpg` — Hoolock Gibbon
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of hoolock gibbon, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B93. `art_wild_great_hornbill.jpg` — Great Hornbill
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of great hornbill, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B94. `art_wild_sarus_crane_pair.jpg` — Sarus Crane Pair
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of sarus crane pair, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B95. `art_wild_flamingo_flock.jpg` — Flamingo Flock
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of flamingo flock, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B96. `art_wild_great_indian_bustard.jpg` — Great Indian Bustard
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of great Indian bustard, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B97. `art_wild_nilgiri_tahr.jpg` — Nilgiri Tahr
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of Nilgiri tahr, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B98. `art_wild_lion_tailed_macaque.jpg` — Lion-Tailed Macaque
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of lion-tailed macaque, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B99. `art_wild_purple_frog.jpg` — Purple Frog
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of purple frog, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B100. `art_wild_four_horned_antelope.jpg` — Four-Horned Antelope
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of four-horned antelope, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B101. `art_wild_mouse_deer.jpg` — Mouse Deer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of mouse deer, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B102. `art_wild_clouded_leopard.jpg` — Clouded Leopard
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of clouded leopard, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B103. `art_wild_red_panda.jpg` — Red Panda
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of red panda, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B104. `art_wild_slow_loris.jpg` — Slow Loris
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of slow loris, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B105. `art_wild_dugong.jpg` — Dugong
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of dugong, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B106. `art_wild_pygmy_hog.jpg` — Pygmy Hog
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of pygmy hog, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B107. `art_wild_nilgiri_marten.jpg` — Nilgiri Marten
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of Nilgiri marten, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B108. `art_wild_nicobar_pigeon.jpg` — Nicobar Pigeon
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of Nicobar pigeon, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B109. `art_wild_black_necked_crane.jpg` — Black-Necked Crane
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of black-necked crane, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B110. `art_wild_painted_stork.jpg` — Painted Stork
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of painted stork, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B111. `art_wild_spot_billed_pelican.jpg` — Spot-Billed Pelican
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of spot-billed pelican, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B112. `art_wild_indian_skimmer.jpg` — Indian Skimmer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stylised folk-art wildlife portrait of Indian skimmer, dotted Gond-style patterning, ivory ground, jewel-tone accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B113. `art_tribelife_longhouse_drum_night.jpg` — Longhouse Drum Night
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: longhouse drum night, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B114. `art_tribelife_terrace_millet_harvest.jpg` — Terrace Millet Harvest
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: terrace millet harvest, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B115. `art_tribelife_bamboo_loom_weaving.jpg` — Bamboo Loom Weaving
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: bamboo loom weaving, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B116. `art_tribelife_river_fish_weir.jpg` — River Fish Weir
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: river fish weir, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B117. `art_tribelife_weekly_haat_market.jpg` — Weekly Haat Market
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: weekly haat market, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B118. `art_tribelife_forest_resin_tapping.jpg` — Forest Resin Tapping
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: forest resin tapping, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B119. `art_tribelife_iron_bloom_smelting.jpg` — Iron Bloom Smelting
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: iron bloom smelting, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B120. `art_tribelife_jhum_hill_sowing.jpg` — Jhum Hill Sowing
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: jhum hill sowing, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B121. `art_tribelife_log_drum_festival.jpg` — Log-Drum Festival
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: log-drum festival, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B122. `art_tribelife_sacred_grove_gathering.jpg` — Sacred Grove Gathering
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: sacred grove gathering, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B123. `art_tribelife_ancestor_stone_memorials.jpg` — Ancestor Stone Memorials
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: ancestor stone memorials, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B124. `art_tribelife_mask_carving_workshop.jpg` — Mask Carving Workshop
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: mask carving workshop, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B125. `art_tribelife_dugout_boat_making.jpg` — Dugout Boat Making
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: dugout boat making, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B126. `art_tribelife_hill_market_trek.jpg` — Hill Market Trek
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: hill market trek, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B127. `art_tribelife_fire_circle_dance.jpg` — Fire-Circle Dance
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: fire-circle dance, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B128. `art_tribelife_clay_granary_making.jpg` — Clay Granary Making
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: clay granary making, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B129. `art_tribelife_monsoon_sowing_songs.jpg` — Monsoon Sowing Songs
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: monsoon sowing songs, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B130. `art_tribelife_harvest_feast.jpg` — Harvest Feast
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: harvest feast, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B131. `art_tribelife_village_wrestling_akhara.jpg` — Village Wrestling Akhara
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: village wrestling akhara, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B132. `art_tribelife_tattoo_artisan_at_work.jpg` — Tattoo Artisan At Work
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — documentary folk illustration of tribal life: tattoo artisan at work, respectful and celebratory, warm earthy palette, ivory ground. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B133. `art_neon_sitar.jpg` — Sitar
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of sitar on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B134. `art_neon_tabla_pair.jpg` — Tabla Pair
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of tabla pair on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B135. `art_neon_bangle_stack.jpg` — Bangle Stack
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of bangle stack on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B136. `art_neon_marigold_garland.jpg` — Marigold Garland
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of marigold garland on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B137. `art_neon_brass_diya.jpg` — Brass Diya
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of brass diya on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B138. `art_neon_conch_shell.jpg` — Conch Shell
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of conch shell on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B139. `art_neon_peacock_feather.jpg` — Peacock Feather
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of peacock feather on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B140. `art_neon_temple_gopuram.jpg` — Temple Gopuram
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of temple gopuram on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B141. `art_neon_lotus_pond.jpg` — Lotus Pond
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of lotus pond on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B142. `art_neon_classical_dancer.jpg` — Classical Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of classical dancer on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B143. `art_neon_dholak_drum.jpg` — Dholak Drum
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of dholak drum on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B144. `art_neon_veena.jpg` — Veena
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of veena on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B145. `art_neon_tanpura.jpg` — Tanpura
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of tanpura on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B146. `art_neon_ghungroo_anklet.jpg` — Ghungroo Anklet
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of ghungroo anklet on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B147. `art_neon_morchhal_fan.jpg` — Morchhal Fan
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of morchhal fan on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B148. `art_neon_jhula_swing.jpg` — Jhula Swing
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of jhula swing on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B149. `art_neon_bullock_cart.jpg` — Bullock Cart
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of bullock cart on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B150. `art_neon_fishing_sail.jpg` — Fishing Sail
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — glowing hand-bent neon-tube artwork of fishing sail on a charcoal wall, warm tube glow, soft halo. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B151. `art_cnc_jaali_jharokha.jpg` — Jaali Jharokha
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of jaali jharokha, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B152. `art_cnc_temple_doorway.jpg` — Temple Doorway
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of temple doorway, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B153. `art_cnc_banyan_roots.jpg` — Banyan Roots
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of banyan roots, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B154. `art_cnc_lotus_mandala.jpg` — Lotus Mandala
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of lotus mandala, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B155. `art_cnc_paisley_vine.jpg` — Paisley Vine
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of paisley vine, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B156. `art_cnc_peacock_arch.jpg` — Peacock Arch
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of peacock arch, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B157. `art_cnc_sunburst_rays.jpg` — Sunburst Rays
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of sunburst rays, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B158. `art_cnc_monsoon_clouds.jpg` — Monsoon Clouds
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of monsoon clouds, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B159. `art_cnc_conch_spiral.jpg` — Conch Spiral
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of conch spiral, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B160. `art_cnc_bangle_circles.jpg` — Bangle Circles
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of bangle circles, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B161. `art_cnc_mehndi_lace.jpg` — Mehndi Lace
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of mehndi lace, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B162. `art_cnc_kolam_dots.jpg` — Kolam Dots
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of kolam dots, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B163. `art_cnc_river_bend.jpg` — River Bend
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of river bend, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B164. `art_cnc_mountain_layers.jpg` — Mountain Layers
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of mountain layers, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B165. `art_cnc_forest_canopy.jpg` — Forest Canopy
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of forest canopy, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B166. `art_cnc_bird_flock.jpg` — Bird Flock
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of bird flock, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B167. `art_cnc_toran_arch.jpg` — Toran Arch
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of toran arch, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B168. `art_cnc_temple_bell.jpg` — Temple Bell
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — impossible multi-layer CNC-cut wooden frame artwork of temple bell, laser-cut depth extending beyond the canvas. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B169. `art_emboss_temple_spire.jpg` — Temple Spire
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of temple spire sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B170. `art_emboss_peacock_feather_eye.jpg` — Peacock Feather Eye
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of peacock feather eye sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B171. `art_emboss_lotus_pod.jpg` — Lotus Pod
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of lotus pod sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B172. `art_emboss_paisley_cluster.jpg` — Paisley Cluster
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of paisley cluster sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B173. `art_emboss_mango_motif.jpg` — Mango Motif
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of mango motif sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B174. `art_emboss_bangle_stack.jpg` — Bangle Stack
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of bangle stack sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B175. `art_emboss_kolam_grid.jpg` — Kolam Grid
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of kolam grid sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B176. `art_emboss_terracotta_horse.jpg` — Terracotta Horse
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of terracotta horse sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B177. `art_emboss_temple_bell.jpg` — Temple Bell
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of temple bell sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B178. `art_emboss_conch_shell.jpg` — Conch Shell
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of conch shell sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B179. `art_emboss_toran_hanging.jpg` — Toran Hanging
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of toran hanging sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B180. `art_emboss_diya_row.jpg` — Diya Row
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of diya row sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B181. `art_emboss_brass_lamp.jpg` — Brass Lamp
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of brass lamp sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B182. `art_emboss_tulsi_plant.jpg` — Tulsi Plant
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of tulsi plant sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B183. `art_emboss_marigold_string.jpg` — Marigold String
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of marigold string sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B184. `art_emboss_silk_sari_border.jpg` — Silk Sari Border
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of silk sari border sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B185. `art_emboss_zardozi_vine.jpg` — Zardozi Vine
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of zardozi vine sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B186. `art_emboss_block_print_stamp.jpg` — Block-Print Stamp
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — stacked embossed relief layers of block-print stamp sealed under glossy acrylic, high-gloss reflections, sculpted depth. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B187. `art_acrylic_desert_caravan.jpg` — Desert Caravan
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: desert caravan, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B188. `art_acrylic_monsoon_peacock_pair.jpg` — Monsoon Peacock Pair
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: monsoon peacock pair, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B189. `art_acrylic_puppet_theatre.jpg` — Puppet Theatre
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: puppet theatre, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B190. `art_acrylic_snake_boat_race.jpg` — Snake-Boat Race
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: snake-boat race, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B191. `art_acrylic_bihu_drummers.jpg` — Bihu Drummers
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Bihu drummers, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B192. `art_acrylic_theyyam_fire_ritual.jpg` — Theyyam Fire Ritual
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Theyyam fire ritual, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B193. `art_acrylic_yakshagana_stage.jpg` — Yakshagana Stage
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Yakshagana stage, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B194. `art_acrylic_lavani_dancer.jpg` — Lavani Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Lavani dancer, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B195. `art_acrylic_bhangra_drummers.jpg` — Bhangra Drummers
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Bhangra drummers, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B196. `art_acrylic_ghoomar_swirl.jpg` — Ghoomar Swirl
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Ghoomar swirl, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B197. `art_acrylic_chhau_mask_dancer.jpg` — Chhau Mask Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Chhau mask dancer, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B198. `art_acrylic_manipuri_dancer.jpg` — Manipuri Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Manipuri dancer, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B199. `art_acrylic_mohiniyattam_pose.jpg` — Mohiniyattam Pose
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Mohiniyattam pose, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B200. `art_acrylic_odissi_dancer.jpg` — Odissi Dancer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Odissi dancer, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B201. `art_acrylic_bharatanatyam_mudra.jpg` — Bharatanatyam Mudra
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Bharatanatyam mudra, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B202. `art_acrylic_kathak_chakkar_spin.jpg` — Kathak Chakkar Spin
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Kathak chakkar spin, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B203. `art_acrylic_kuchipudi_tarangam.jpg` — Kuchipudi Tarangam
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Kuchipudi tarangam, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B204. `art_acrylic_baul_ektara_singer.jpg` — Baul Ektara Singer
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — bold expressive acrylic painting on canvas: Baul ektara singer, gallery lighting, thick impasto accents. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B205. `art_room_bedroom_peacock_wall.jpg` — Bedroom Peacock Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, bedroom peacock wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B206. `art_room_study_gond_forest_wall.jpg` — Study Gond-Forest Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, study gond-forest wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B207. `art_room_living_room_phad_scroll_wall.jpg` — Living-Room Phad Scroll Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, living-room phad scroll wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B208. `art_room_nursery_warli_wall.jpg` — Nursery Warli Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, nursery warli wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B209. `art_room_foyer_madhubani_wall.jpg` — Foyer Madhubani Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, foyer madhubani wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B210. `art_room_corridor_kalamkari_wall.jpg` — Corridor Kalamkari Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, corridor kalamkari wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B211. `art_room_staircase_phulkari_wall.jpg` — Staircase Phulkari Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, staircase phulkari wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B212. `art_room_puja_room_lotus_wall.jpg` — Puja-Room Lotus Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, puja-room lotus wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B213. `art_room_balcony_backwater_wall.jpg` — Balcony Backwater Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, balcony backwater wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B214. `art_room_cafe_ajrak_wall.jpg` — Cafe Ajrak Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, cafe ajrak wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B215. `art_room_boutique_chikankari_wall.jpg` — Boutique Chikankari Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, boutique chikankari wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B216. `art_room_lobby_sun_wheel_wall.jpg` — Lobby Sun-Wheel Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, lobby sun-wheel wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B217. `art_room_reading_nook_forest_wall.jpg` — Reading Nook Forest Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, reading nook forest wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B218. `art_room_music_room_sitar_wall.jpg` — Music Room Sitar Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, music room sitar wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B219. `art_room_guest_room_paisley_wall.jpg` — Guest Room Paisley Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, guest room paisley wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B220. `art_room_sunroom_peacock_wall.jpg` — Sunroom Peacock Wall
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — photorealistic Indian home interior, sunroom peacock wall as the focal art piece in a laser-engraved wood frame. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B221. `art_cutout_dancer_silhouette.jpg` — Dancer Silhouette
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of dancer silhouette, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B222. `art_cutout_peacock.jpg` — Peacock
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of peacock, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B223. `art_cutout_paisley.jpg` — Paisley
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of paisley, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B224. `art_cutout_banyan_tree.jpg` — Banyan Tree
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of banyan tree, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B225. `art_cutout_kolam.jpg` — Kolam
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of kolam, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B226. `art_cutout_country_boat.jpg` — Country Boat
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of country boat, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B227. `art_cutout_elephant_parade.jpg` — Elephant Parade
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of elephant parade, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B228. `art_cutout_temple_spire.jpg` — Temple Spire
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of temple spire, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B229. `art_cutout_lotus.jpg` — Lotus
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of lotus, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B230. `art_cutout_fish_pair.jpg` — Fish Pair
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of fish pair, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B231. `art_cutout_sun_and_moon.jpg` — Sun And Moon
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of sun and moon, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B232. `art_cutout_sitar.jpg` — Sitar
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — frameless laser-cut acrylic artwork of sitar, glowing edge-lit rim, floating on an ivory wall. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B233. `art_laserlit_temple_bell.jpg` — Temple Bell
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of temple bell lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B234. `art_laserlit_conch.jpg` — Conch
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of conch lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B235. `art_laserlit_peacock_feather.jpg` — Peacock Feather
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of peacock feather lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B236. `art_laserlit_kolam.jpg` — Kolam
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of kolam lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B237. `art_laserlit_paisley.jpg` — Paisley
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of paisley lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B238. `art_laserlit_elephant.jpg` — Elephant
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of elephant lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B239. `art_laserlit_bird_flock.jpg` — Bird Flock
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of bird flock lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B240. `art_laserlit_mountain_ridge.jpg` — Mountain Ridge
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of mountain ridge lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B241. `art_laserlit_river_sail.jpg` — River Sail
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of river sail lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B242. `art_laserlit_moon_pond.jpg` — Moon Pond
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of moon pond lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B243. `art_laserlit_sun_rays.jpg` — Sun Rays
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of sun rays lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B244. `art_laserlit_mandala.jpg` — Mandala
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — laser-engraved acrylic panel of mandala lit from within, engraved lines glowing warm gold. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B245. `art_backlit_jaali_lattice.jpg` — Jaali Lattice
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of jaali lattice, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B246. `art_backlit_lotus_pond.jpg` — Lotus Pond
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of lotus pond, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B247. `art_backlit_peacock_fan.jpg` — Peacock Fan
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of peacock fan, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B248. `art_backlit_temple_at_dawn.jpg` — Temple At Dawn
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of temple at dawn, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B249. `art_backlit_banyan_at_dusk.jpg` — Banyan At Dusk
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of banyan at dusk, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B250. `art_backlit_kolam_at_night.jpg` — Kolam At Night
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of kolam at night, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B251. `art_backlit_mountain_dawn.jpg` — Mountain Dawn
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of mountain dawn, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B252. `art_backlit_river_sunset_sail.jpg` — River Sunset Sail
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of river sunset sail, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B253. `art_backlit_fire_dancers.jpg` — Fire Dancers
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of fire dancers, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B254. `art_backlit_marigold_garland.jpg` — Marigold Garland
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of marigold garland, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B255. `art_backlit_paisley_weave.jpg` — Paisley Weave
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of paisley weave, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B256. `art_backlit_bird_flock_at_dawn.jpg` — Bird Flock At Dawn
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — backlit fabric translite panel of bird flock at dawn, even soft glow, rich saturated colours. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B257. `art_creative_toy_train_in_the_hills.jpg` — Toy Train In The Hills
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: toy train in the hills, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B258. `art_creative_puppet_caravan.jpg` — Puppet Caravan
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: puppet caravan, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B259. `art_creative_bullock_cart_at_sunset.jpg` — Bullock Cart At Sunset
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: bullock cart at sunset, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B260. `art_creative_village_well_gathering.jpg` — Village Well Gathering
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: village well gathering, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B261. `art_creative_swing_under_the_banyan.jpg` — Swing Under The Banyan
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: swing under the banyan, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B262. `art_creative_fireflies_over_fields.jpg` — Fireflies Over Fields
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: fireflies over fields, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B263. `art_creative_paper_boats_in_rain.jpg` — Paper Boats In Rain
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: paper boats in rain, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B264. `art_creative_lantern_night_market.jpg` — Lantern Night Market
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: lantern night market, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B265. `art_creative_kolam_at_morning_door.jpg` — Kolam At Morning Door
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: kolam at morning door, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B266. `art_creative_haat_bazaar_bustle.jpg` — Haat Bazaar Bustle
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: haat bazaar bustle, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B267. `art_creative_mountain_terrace_fields.jpg` — Mountain Terrace Fields
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: mountain terrace fields, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B268. `art_creative_coastal_salt_pans.jpg` — Coastal Salt Pans
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: coastal salt pans, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B269. `art_creative_fishing_sails_at_dawn.jpg` — Fishing Sails At Dawn
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: fishing sails at dawn, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B270. `art_creative_potter_s_wheel.jpg` — Potter'S Wheel
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: potter's wheel, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B271. `art_creative_loom_song.jpg` — Loom Song
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: loom song, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.

### B272. `art_creative_brass_makers_at_work.jpg` — Brass Makers At Work
> Square 1:1 premium canvas art print for the ArtVision DesiMuseum collection — editorial creative concept art: brass makers at work, joyful surreal folk-realism, ivory ground, warm festival palette. Warm ivory ground, vermillion-ochre-teal-charcoal palette with subtle gold accents, museum-grade composition, 400 GSM UV canvas print texture. No text, no watermark, no border.
