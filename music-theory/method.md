# method.md
**Purpose**: Instructions for the AI agent on how to work through the Music Theory Learning Roadmap.

---

## Core Principles

- The **user** always decides which section to tackle next.
- The agent never jumps ahead or chooses the next topic on its own.
- After completing a section, the agent updates the roadmap by ticking off the relevant items.
- All generated notes must be clean, self-contained Obsidian-ready Markdown.
- File names follow **numbered kebab-case** (no spaces), e.g. `02-ancient-greek-theory.md`.

---

## Workflow

When the user says something like:

> “Let’s tackle Ancient Greek Theory”  
> or  
> “Do section 2.1”  
> or  
> “Generate the note for Pythagorean tuning”

The agent should follow these steps:

### 1. Confirm the scope
Briefly restate what will be covered so the user can correct it if needed.

### 2. Generate the note(s)
Create one or more well-structured Markdown files containing:
- Clear headings
- Explanations in plain language
- Tables or lists where useful
- Key terms in **bold** on first use
- Short summary at the end (optional but helpful)

Suggested file naming:
- Main topic note: `02-ancient-greek-theory.md`
- Sub-topic notes (if needed): `02a-tetrachords-and-genera.md`, `02b-pythagorean-tuning.md`

### 3. Update the roadmap
After generating the content, show the relevant section of `00-music-theory-learning-roadmap.md` with the completed items ticked off, for example:

```markdown
### 2.1 Ancient Greek Theory
- [x] Tetrachords (the basic building block)
- [x] The three genera:
  - Diatonic
  - Chromatic
  - Enharmonic
- [x] Original Greek meaning of the mode names
- [x] How Greek theory differs from the later medieval system
- [x] Pythagorean tuning system
  - Ratios based on the pure fifth (3:2)
  - Pythagorean comma
  - Strengths and problems of the system
```

### 4. Offer next actions
End by asking the user what they would like to do next (e.g. go deeper on a sub-point, move to the next section, revise something, etc.).

---

## Style Guidelines for Generated Notes

- Use simple, clear language.
- Prefer short paragraphs and bullet points over long blocks of text.
- Include historical context when relevant, but keep the focus on understanding.
- When explaining tuning systems or intervals, use both ratios and approximate cent values if helpful.
- Always write in a way that future-you can understand without needing the original chat.

---

## Example User Commands

- “Start with section 2.1 – Ancient Greek Theory”
- “Make a detailed note on tetrachords and the three genera”
- “Do Pythagorean tuning next”
- “Tick off everything we’ve done in Phase 1 and show me the updated roadmap”

---

**Remember**: The user is the one driving the sequence. The agent’s job is to execute cleanly, document well, and keep the roadmap up to date.
