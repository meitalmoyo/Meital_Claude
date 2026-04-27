# Visual Design — ch05: Web & Digital

WordPress, Wix, and digital design patterns.

---

## Web Design Fundamentals

**Color mode: RGB** (not CMYK — that's print only)

**Resolution:** 72 DPI for screen. Images should be sized at their display dimensions — no point sending a 4000px image to display at 400px.

**File formats:**
- JPG — photos, complex images (lossy compression, small file size)
- PNG — logos, graphics with transparency (lossless, larger files)
- SVG — icons, logos for web (vector, scales perfectly, tiny file size)
- WebP — modern web format, best compression — use where supported
- GIF/MP4 — short animations (prefer MP4 for quality)

---

## Hebrew Website Considerations

**RTL layout:** Hebrew is right-to-left. WordPress and Wix both support RTL but need to be configured:
- WordPress: use a theme that supports RTL, or add `direction: rtl` to CSS
- Wix: built-in RTL toggle in site settings

**Font choices for Hebrew:**
- System fonts (Arial, Tahoma) are safe but generic
- Google Fonts has growing Hebrew support (Assistant, Heebo, Rubik — all recommended)
- Check that the chosen font includes Hebrew characters before designing around it

**Bilingual sites:** If the site has both Hebrew and English sections, decide on the layout direction per language. Don't use RTL layout for English content.

---

## WordPress

**Key decisions before starting:**
- Block editor (Gutenberg) or classic editor? Gutenberg is standard now.
- Page builder plugin? (Elementor, Divi) — useful for complex layouts but adds bloat
- Hosting: Israeli clients often use Israeli hosts (SiteGround Israel, Israeli resellers) — check with client

**Performance basics:**
- Compress all images before upload (use TinyPNG or Smush plugin)
- Use a caching plugin (WP Super Cache, W3 Total Cache)
- Limit plugins — every plugin adds load time

**Handoff to client:**
- Create a user account with Editor or Author role (not Admin unless they need it)
- Document how to update their own content — a simple guide saves support calls

---

## Wix

**Good for:** Small businesses, portfolios, simple service sites — fast setup, no hosting to manage

**Limitations:** Less flexible than WordPress, harder to do custom code, not ideal for complex functionality

**Wix SEO:** Use the SEO Wiz setup, fill in meta titles and descriptions for every page, add alt text to all images

---

## Digital Asset Specs (Social Media, Israeli clients)

| Platform | Post | Story/Reel |
|----------|------|-----------|
| Instagram | 1080×1080px | 1080×1920px |
| Facebook | 1200×630px | 1080×1920px |
| LinkedIn | 1200×627px | — |
| WhatsApp status | — | 1080×1920px |

**Note:** WhatsApp is heavily used in Israeli business communication. Stories/status formats for WhatsApp are common deliverables.
