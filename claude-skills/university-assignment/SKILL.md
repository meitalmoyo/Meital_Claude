---
name: University Assignment
description: Help Meital write, structure, and review academic assignments for Bar Ilan Master's degree in Conflict Management & Negotiation
argument-hint: (assignment topic or course name)
user_invocable: true
---

# When to trigger
- User mentions a university assignment, essay, paper, or homework
- User says "Bar Ilan", "assignment", "מטלה", "עבודה אקדמית"

# When NOT to trigger
- General questions about mediation theory (use the book instead)
- LinkedIn or professional content writing

# Execution Workflow

1. **Load context**
   - Read `me/profile.md` — who Meital is
   - Read `books/mediation-conflict-resolution/_toc.md` — what we know
   - Read the relevant chapter if the topic exists

2. **Understand the assignment**
   - Ask: What is the topic? What are the instructions? Word count? Submission date?
   - Ask: Is there a specific theorist, case, or framework to focus on?

3. **Structure first**
   - Propose an outline before writing
   - Wait for approval before drafting

4. **Write**
   - Academic Hebrew unless otherwise specified
   - Formal academic tone (see `me/tone-of-voice.md`)
   - Structured arguments, citations where relevant
   - Follow Bar Ilan academic standards

5. **Review**
   - Check for logical flow, academic language, completeness
   - Suggest improvements if needed

# Post-task Learning Loop
After completing an assignment:
- Did we encounter a new theory or concept? → Add to `books/mediation-conflict-resolution/` relevant chapter
- Did a specific structure work well? → Note in `ch06-academic-foundations.md`
- Did something go wrong (wrong format, missed requirement)? → Add to `ch08-known-gotchas.md`
