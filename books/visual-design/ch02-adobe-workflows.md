# Visual Design — ch02: Adobe Workflows

Practical tips, shortcuts, and file discipline for Adobe Suite at MOYO Productions.

---

## Illustrator

**Essential shortcuts:**
- `Cmd/Ctrl + D` — Transform again (repeat last move/scale/rotate)
- `Cmd/Ctrl + G` — Group
- `Cmd/Ctrl + Shift + G` — Ungroup
- `Alt + drag` — Duplicate object
- `Shift + O` — Artboard tool
- `Cmd/Ctrl + Alt + B` — Make blend
- `Object > Expand Appearance` — flatten complex effects before exporting

**File discipline:**
- Name artboards clearly (not "Artboard 1, 2, 3")
- Keep layers organized: Background → Content → Text → Guides
- Embed images or package the file before sending — linked images break on other machines
- Always save a working `.ai` file AND export the deliverable separately — never overwrite the source

**Print-ready from Illustrator:**
- Switch color mode to CMYK: File > Document Color Mode > CMYK
- Add bleed in Document Setup (3mm minimum for standard print)
- Outline all fonts before exporting to PDF: Select All → Type > Create Outlines
- Export as PDF/X-1a for professional print

**AI tools integration:**
- Krea AI → generate reference images → trace or redraw in Illustrator
- Keep AI-generated assets in a separate layer labeled "AI-ref" so it's clear what's generated vs original

---

## After Effects

**Project setup:**
- Match composition settings to delivery format before starting (don't resize after)
- Common formats: 1920×1080 (Full HD), 3840×2160 (4K), 1080×1920 (vertical/Reels)
- Frame rates: 25fps (PAL/European standard, Israeli TV), 30fps (web), 24fps (cinematic)

**Essential shortcuts:**
- `U` — Show all keyframed properties on selected layer
- `UU` — Show all modified properties
- `P/S/R/T/A` — Position / Scale / Rotation / Opacity / Anchor point
- `Cmd/Ctrl + D` — Duplicate layer
- `Alt + [` or `]` — Trim layer in/out to current time
- `Spacebar` — Preview (RAM preview with `0` on numpad)

**Workflow discipline:**
- Pre-compose complex layer groups — keeps the timeline readable
- Name every layer — "Layer 1" is not acceptable past the prototype stage
- Use shape layers over PNGs where possible — they're resolution-independent
- Render queue vs Media Encoder: for batch exports or H.264, use Media Encoder

**Motion design principles:**
- Ease in/ease out on every keyframe — linear motion looks robotic
- Graph editor is mandatory for polished animation
- 12 frames (at 25fps) is a standard short animation beat — enough time for the eye to register but not drag
- Less is more: one strong motion beats five competing ones

---

## File Organization (All Adobe Apps)

```
Client_ProjectName/
├── _Source/           ← working files (.ai, .aep, .psd)
├── _Assets/           ← fonts, images, logos, supplied files
├── _Exports/          ← final deliverables
│   ├── Print/
│   └── Digital/
└── _Client-Feedback/  ← their comments, annotated PDFs
```

**Naming convention:** `ClientName_ProjectName_v01.ai` → `_v02` → `_FINAL`
Never name a file "FINAL_FINAL" — that's a sign the version system broke down.
