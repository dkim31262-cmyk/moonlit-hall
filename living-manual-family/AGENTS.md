# AGENTS.md — MOON × PAKIN Living Manual

This folder is intended for collaboration across AI systems and human editors.

## Non-negotiable canon
1. Bilingual by default: Thai + English.
2. Breathing Editorial Architecture: whitespace is material, not waste.
3. Product first · Tool optional.
4. One dominant thing + one supporting thing + one next action per primary viewport.
5. No card farm unless cards materially improve information architecture.
6. Stop when another tool adds nothing.
7. Preserve human agency. Tools compose; humans decide.

## Editing protocol
- Read the current artifact before changing it.
- Improve the smallest surface that solves the problem.
- Keep Thai translation natural and equivalent in meaning, not word-for-word.
- Preserve mobile readability and accessibility.
- If changing tool-routing logic, explain why.
- Preferred: branch + pull request. Direct main updates only when Moon explicitly asks for direct update.

## Files
- index.html — standalone Living Manual
- family-state.json — portable state/canon
- README.md — human handoff
- AGENTS.md — AI collaboration contract


## Family handoff protocol
When another AI receives this folder:
1. Read `AGENTS.md` and `family-state.json` first.
2. Inspect the current `index.html` before proposing changes.
3. Preserve bilingual behavior and the breathing editorial architecture.
4. Prefer a small, reversible change over rebuilding the whole system.
5. Return either a branch/PR or an updated handoff JSON plus a concise change note.
