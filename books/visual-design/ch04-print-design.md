# Visual Design — ch04: Print Design

Specs, file prep, and print-ready delivery. This is where mistakes cost money.

---

## Color Mode

**Always CMYK for print.** RGB colors look different when converted — check the conversion before sending.

**Spot colors (Pantone)** — used when exact brand color is critical (logos, brand materials). More expensive to print. Confirm with the printer whether they support spot colors.

**Black in print:**
- Regular black text: `K: 100` only (not rich black)
- Rich black for large areas: `C:60 M:40 Y:40 K:100` — deeper, but bleeds more at small sizes
- Never use rich black for text under 14pt — it smears

---

## Bleed & Margins

**Standard bleed:** 3mm on all sides (some printers require 5mm — always confirm)

**Safe zone (margin):** Keep all important content at least 5mm from the trim line. Text too close to the edge gets cut.

**Rule of thumb:**
```
[Bleed edge] ← 3mm → [Trim line] ← 5mm → [Safe zone]
```

---

## Resolution

**Minimum 300 DPI for print.** 72 DPI is screen resolution — it will look pixelated in print.

**Vector files (Illustrator .ai, .eps, .pdf)** — resolution-independent, always print sharp. Preferred for logos and clean graphics.

**Raster images** — check resolution at the size they'll be printed, not the original file size. A 300 DPI image shrinks when scaled up.

---

## Common Print Formats (Israeli market)

| Format | Dimensions | Common use |
|--------|-----------|------------|
| A4 | 210 × 297mm | Documents, flyers, menus |
| A5 | 148 × 210mm | Brochures, small flyers |
| A3 | 297 × 420mm | Posters |
| Business card | 85 × 55mm | Standard; 90×50 also used |
| Roll-up banner | 85 × 200cm | Events, exhibitions |

**Always confirm dimensions with the printer** — Israeli printers sometimes use non-standard sizes.

---

## File Delivery for Print

**Preferred format:** PDF/X-1a (most compatible with professional printers)

**Checklist before sending:**
- [ ] Color mode: CMYK
- [ ] Resolution: 300 DPI minimum
- [ ] Bleed: 3mm (or as specified)
- [ ] Fonts: outlined / embedded
- [ ] Links: embedded, not linked
- [ ] No RGB or spot colors (unless specified)
- [ ] Correct dimensions in the file
- [ ] Saved as PDF, not AI or PSD

**How to export PDF from Illustrator:**
File > Save As > Adobe PDF > PDF/X-1a:2001 preset > Marks and Bleeds > check "Use Document Bleed Settings" > Save PDF

---

## Working with Printers (Israel)

- Get a digital proof (PDF proof) before going to press for large orders
- Ask for a physical proof for anything with exact brand colors
- Confirm paper weight and finish (matte/glossy/laminated) in writing before printing
- Check turnaround time — Israeli printers vary widely (1 day rush vs 5 days standard)
