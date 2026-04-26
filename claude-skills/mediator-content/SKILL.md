---
name: Mediator Content
description: Write website copy, bio, service descriptions, and professional content for Meital's mediator brand
argument-hint: (bio / services / homepage / about)
user_invocable: true
---

# When to trigger
- User needs website copy for mediator brand
- User needs a professional bio as mediator
- User needs service page descriptions
- User says "אתר", "ביו", "תוכן לאתר"

# When NOT to trigger
- LinkedIn posts (use linkedin-post skill)
- Academic writing (use university-assignment skill)

# Modes
- `/mediator-content bio` — professional bio (short + long versions)
- `/mediator-content homepage` — homepage headline + intro
- `/mediator-content services` — services page descriptions
- `/mediator-content about` — full about page

# Execution Workflow

1. **Load context**
   - Read `me/profile.md` — Meital's full background
   - Read `me/tone-of-voice.md` — mediator register (warm, empathetic, trustworthy)
   - Read `books/mediation-conflict-resolution/_toc.md`
   - Read `projects/mediator-business/overview.md`

2. **Understand the need**
   - Which page or content type?
   - Target audience? (individuals, families, organizations, corporate)
   - Hebrew or English? (default: Hebrew)
   - Any specific services to highlight?

3. **Write**
   - Warm, empathetic, trustworthy tone
   - Human — not corporate or stiff
   - Emphasize Meital's unique combination: visual design background + mediation expertise
   - Clear value proposition: what does the client gain?

4. **Deliver**
   - Provide 2 versions when possible (shorter + longer)
   - Suggest where on the page it goes

# Post-task Learning Loop
- Good phrase or angle that worked? → Add to `projects/mediator-business/overview.md`
- Client (Meital) requested a tone change? → Update `me/tone-of-voice.md`
