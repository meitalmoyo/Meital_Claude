---
name: Design Brief
description: Generate client briefs, project specs, and proposals for MOYO Productions design work
argument-hint: (project type: print / web / video / branding)
user_invocable: true
---

# When to trigger
- User needs to write a client brief, proposal, or project spec
- User mentions a new design project or client
- User says "brief", "הצעת מחיר", "מפרט"

# When NOT to trigger
- Already has a brief and needs design help
- LinkedIn or mediator content

# Modes
- `/design-brief print` — print project brief
- `/design-brief web` — website project brief
- `/design-brief video` — video/animation brief
- `/design-brief branding` — branding/identity brief

# Execution Workflow

1. **Load context**
   - Read `me/profile.md` — MOYO Productions services
   - Read `books/visual-design/ch03-client-patterns.md` if it exists

2. **Gather project info**
   Ask:
   - Who is the client and what do they do?
   - What is the deliverable? (flyer, logo, video, website...)
   - What is the deadline?
   - Any references, style preferences, or restrictions?
   - Budget range? (optional)

3. **Generate brief**
   - Clear project scope
   - Deliverables list
   - Timeline
   - What client needs to provide (content, images, approvals)
   - Revision policy

4. **Output**
   - Ready to send to client (professional tone)
   - Hebrew or English based on client

# Post-task Learning Loop
- Unusual client request? → Add to `books/visual-design/ch03-client-patterns.md`
- Something went wrong with scope or expectations? → Add to `ch08-known-gotchas.md`
