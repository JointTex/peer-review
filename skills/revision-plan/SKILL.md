---
name: revision-plan
description: Sort reviewer and editor comments into a revision plan, with an action, an owner and a status for each point, before any reply is written.
---

Use this when a decision letter has arrived and the authors need to agree on what to do before writing the response or touching the manuscript.

1. Get the decision letter and every review. Ask for them if they are not in the conversation or the project; read a PDF with read_pdf. Never reconstruct comments from memory.
2. Ask for the decision, the deadline, and which journal or venue it is.
3. Split the text into numbered points, keeping each source's order: E.1, E.2 for the editor, 1.1, 1.2 for Reviewer 1, and so on. One point per request; a paragraph that asks for three things is three points. Keep the reviewer's wording, shortened only when long.
4. Read the manuscript passages each point is about. Note where a point is already met in the manuscript and the reviewer appears to have missed it.
5. Classify each point:
   - type: new experiment or analysis, new data, rewrite or reorganisation, clarification, added citation or discussion of related work, figure or table change, typographical;
   - weight: the editor named it, it bears on the main claim, or it is minor. The editor's letter decides this where it speaks; otherwise say that the weighting is your reading.
6. Group points that are really the same concern raised by several reviewers, and mark pairs that conflict with each other.
7. For each point propose an action, and leave the decision to the collaborator wherever it is a scientific judgment:
   - do it, and say what exactly changes and in which file or section;
   - do part of it, and say which part;
   - answer without changing the manuscript;
   - disagree, with the argument or evidence the reply would rest on.
   Do not plan an experiment or analysis as if its result were known, and do not estimate effort you cannot judge; ask.
8. Write the plan as a table in its own file (revision-plan.md, or a LaTeX table if the collaborator prefers): point, short version of the comment, type, weight, proposed action, where in the manuscript, who does it, status (open, in progress, done, will not do). Leave the owner blank unless the collaborator names one.
9. Above the table give a short reading of the reviews: the two or three concerns the decision most likely turns on, what new work they imply, and whether the deadline looks tight for it. Say plainly when the reviews ask for something the current data cannot support.
10. List the open questions the collaborator has to settle, and offer to turn the agreed plan into the response letter with `response-to-reviewers`. Keep the plan file up to date as points are closed if asked to continue.
