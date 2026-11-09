---
name: "phd-ai-usage-log"
description: Generate a short paragraph entry for the user's PhD GenAI usage log, summarising how an AI agent was used in the current session (writing, code, figures/tables, research/ideas) for university disclosure. Use whenever the user says "log this session", "add to my AI log", "AI usage log", "GenAI disclosure entry", "/phd-ai-usage-log", or asks to record/document how an AI agent was used for their thesis or research — even if they don't say "log" explicitly.
---

# PhD GenAI Usage Log

Produce one short entry describing how GenAI was used in this session, for the user to paste into their note-taking app, for instance, Google and Word documents, Obsidian, Notion, etc. The log will hold hundreds of entries and backs the university's GenAI declaration: records can be produced on request, AI-created or modified content is disclosed, the student takes responsibility for it, and can defend the work in examination.

The entry is evidence, so accuracy matters more than polish. The AI agent writes only what it can observe from the conversation. Conceptualisation and verification are the student's to state, so leave them as TODO unless the user has said them in this conversation. A fabricated disclosure is worse than a blank one. The user is responsible for the accuracy of the entry.

## References

- `references/examples.md`: completed entries. Read before writing to match the expected level of detail.
- `references/Generative Artificial Intelligence in Doctoral Research Guidelines University of Auckland.pdf`: the university's guidelines. Consult when unsure whether a use needs disclosing or how to describe it.

## Format

One short paragraph, plain text, in this order: date, AI model, what was implemented or created, how it was done, where it was conceptualised, how it was verified.

```
DD/MM/YYYY - Used MODEL to WHAT. This was done by HOW. Conceptualised TODO. Verified TODO.
```

## Rules

- Date: the session date as DD/MM/YYYY. If the work clearly spans several days, use a range like 20-22/10/2026.
- Model: the AI model used, e.g. Claude Opus 5.5.
- What: one sentence, specific enough that a supervisor knows what was done, e.g. "implement forward-hook activation extraction for ResNet-50" not "help with code". Say whether AI generated, modified, or only explained. If several distinct uses, join them in the same sentence with semicolons rather than adding lines.
- How: one sentence on the method or approach actually used, naming the key technique, e.g. "deriving dissimilarity matrices between experts within and between models". This is what shows the work is understood, so be concrete and technical, not generic.
- If the user mentions iterations, edits or rejections in the session, add that briefly to the Verified part only if it reflects their checking; otherwise leave TODO.
- Raw text only: no bold, headings, bullets, emoji, angle or square brackets. The output goes in a plain code block so it copies cleanly.
- Keep the whole entry to about four or five short sentences. After the code block, add at most one short line reminding the user to fill the TODOs.
- If the session had no substantive AI use, say so in one line.