# Visual Design — ch06: Video & Animation

After Effects, motion graphics, and delivery formats.

---

## Composition Setup

**Always set up first, never change later.** Changing comp size or frame rate mid-project breaks everything.

| Use case | Resolution | Frame rate |
|----------|-----------|-----------|
| Standard web/social | 1920×1080 | 25 or 30fps |
| Vertical (Reels, TikTok, Stories) | 1080×1920 | 25 or 30fps |
| 4K delivery | 3840×2160 | 25 or 30fps |
| Cinematic look | Any | 24fps |
| Israeli broadcast | 1920×1080 | 25fps (PAL) |

**Duration:** Know the target duration before animating. Adding 10 seconds at the end is easy; cutting 10 seconds of animation is painful.

---

## Animation Principles (Applied)

**Ease in/out on everything.** Go to the Graph Editor. Keyframe velocity curves are the difference between amateur and professional motion.

**Anticipation** — small movement in the opposite direction before the main action. Makes motion feel physical.

**Overshoot** — element goes slightly past its target, then settles back. Creates energy.

**Timing guide:**
- 8–12 frames: snappy, energetic (good for social media)
- 12–18 frames: normal, natural
- 18–24 frames: slow, deliberate, premium feel

**Text animation** — never animate every letter unless you have a reason. Animate by word or line. Letter-by-letter for short words only.

---

## After Effects Workflow

**Layer organization:**
```
[GUIDE] — guides, reference, not rendered
[BG] — background elements
[CONTENT] — main visual elements  
[TEXT] — all text layers
[EFFECTS] — overlays, color grading
```

**Pre-compose early.** Once a group of layers works together, pre-compose it. Keeps the main timeline clean.

**Expressions — the basics:**
- `wiggle(freq, amp)` — adds random movement (e.g., camera shake)
- `time * 360` — continuous rotation
- `loopOut("cycle")` — loops the last keyframe back to first

**RAM preview** — preview at full quality with `0` on numpad. Reduce preview resolution to 1/2 or 1/4 while working, full quality before final review.

---

## AI Tools for Video (Meital's Stack)

**Kling** — AI video generation. Good for background footage, abstract visuals, atmospheric shots. Not for precise character animation.

**Krea AI** — image generation for reference, storyboard frames, or static assets to bring into After Effects.

**Nano Banana** — check specific use cases based on current project needs.

**Workflow with AI:**
1. Generate reference/concept in Krea
2. Generate motion elements in Kling
3. Composite and animate in After Effects
4. Add typography and brand elements in Illustrator → import to AE

---

## Export & Delivery

**For social media / web:**
- Format: H.264 (MP4)
- Use Adobe Media Encoder (not the render queue) for H.264
- Bitrate: 10–20 Mbps for 1080p; 30–50 Mbps for 4K

**For broadcast or archival:**
- Format: ProRes 422 (Mac) or DNxHD (Windows/cross-platform)
- Uncompressed or near-lossless — large files but maximum quality

**For client review:**
- Compress to a reasonable file size for sharing
- Use H.264, keep under 100MB for easy WhatsApp/Drive sharing

**Delivery checklist:**
- [ ] Correct dimensions
- [ ] Correct frame rate
- [ ] Audio mixed and balanced (if applicable)
- [ ] Exported from Media Encoder, not direct render queue (for H.264)
- [ ] File size appropriate for delivery method
- [ ] Filename includes version number
