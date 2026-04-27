# Visual Design — ch08: Known Gotchas

Hard-won lessons. Add to this after every project where something went wrong or surprised you.

---

## How to Log a Gotcha

```
### [Short title of the problem]
**When it happens:** [context]
**What goes wrong:** [the failure]
**Fix / Prevention:** [what to do instead]
**Date discovered:** [YYYY-MM]
```

---

## Print

### RGB file sent to print
**When it happens:** Working in RGB (screen mode) and sending directly to printer without converting
**What goes wrong:** Colors shift significantly — bright screen colors become dull in CMYK print
**Fix / Prevention:** Always switch to CMYK before export. File > Document Color Mode > CMYK. Blues especially lose saturation dramatically.

### Missing bleed on print files
**When it happens:** Designing to exact print size without adding bleed
**What goes wrong:** Printer cuts through the design, leaving white edges
**Fix / Prevention:** Add 3mm bleed in Document Setup from the start. Extend all background elements to the bleed edge.

---

## Adobe Illustrator

### Linked images not embedded
**When it happens:** Sending an Illustrator file to a colleague or printer with linked (not embedded) images
**What goes wrong:** They open the file and images show as missing (broken link icon)
**Fix / Prevention:** Before sending: File > Package (bundles all linked files), or Embed via the Links panel.

### Fonts not outlined for print PDF
**When it happens:** Exporting to PDF without outlining fonts
**What goes wrong:** Printer doesn't have the font, text renders in a substitute font
**Fix / Prevention:** Select All > Type > Create Outlines before exporting. Save a copy — outlined text is no longer editable.

---

## After Effects

### H.264 grayed out in Render Queue
**When it happens:** Trying to render H.264/MP4 directly from After Effects Render Queue
**What goes wrong:** The H.264 option is unavailable in newer AE versions
**Fix / Prevention:** Use Adobe Media Encoder. Queue in AE > Add to Adobe Media Encoder. This is the correct path for H.264.

---

## Client Handoffs

*(Add as discovered)*

---

## Web (WordPress / Wix)

*(Add as discovered)*
