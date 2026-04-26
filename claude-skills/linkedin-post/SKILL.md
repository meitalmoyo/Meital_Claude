---
name: LinkedIn Post
description: Draft LinkedIn posts for Meital's mediator brand — Hebrew, warm professional tone, Israeli audience
argument-hint: (topic or post idea)
user_invocable: true
---

# When to trigger
- User wants to write a LinkedIn post
- User says "פוסט", "LinkedIn", "לינקדאין"

# When NOT to trigger
- Profile rewrite (use mediator-content skill)
- Instagram content (different format)

# Execution Workflow

1. **Load context**
   - Read `me/tone-of-voice.md` — LinkedIn register
   - Read `books/linkedin-content/_toc.md`
   - Read `books/linkedin-content/ch02-content-pillars.md` if it exists
   - Read `books/linkedin-content/ch03-post-formats.md` if it exists

2. **Understand the post**
   - Ask: What's the topic or idea?
   - Ask: Any specific angle, story, or insight to include?
   - If no idea given — suggest 3 options from content pillars

3. **Draft**
   - Hebrew (Israeli professional audience)
   - Warm, empathetic, trustworthy tone
   - Strong opening hook (first line must stop the scroll)
   - Short paragraphs, easy to read on mobile
   - End with a question or call to action

4. **Review**
   - Check hook strength
   - Check tone — not too formal, not too casual
   - Suggest hashtags

# Post-task Learning Loop
After post is published:
- Log the post in `books/linkedin-content/ch07-post-archive.md` with topic and date
- After a few days: note engagement in archive
- Strong hook? → Add pattern to `ch03-post-formats.md`
- Flopped? → Add to `ch08-known-gotchas.md`
