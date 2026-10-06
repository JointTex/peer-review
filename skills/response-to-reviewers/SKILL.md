---
name: response-to-reviewers
description: Draft a point-by-point response to reviewer comments, tied to the changes made in the manuscript.
---

Use this when the collaborator has reviewer or editor comments to answer for a journal revision. For a conference rebuttal with a length limit use `conference-rebuttal`; to sort the comments and agree on what to do before any writing, use `revision-plan` first.

## Before writing

1. Get the comments. Ask for them if they are not in the conversation or in a project file; never reconstruct comments from memory or guess what a reviewer said. If they are in a PDF, read it with read_pdf. Read the decision letter too: the editor's own requests and any point the editor singles out come first.
2. Ask for the decision (minor revision, major revision, reject and resubmit), the deadline, and whether the journal asks for a particular response format or a marked-up manuscript.
3. Read the manuscript sections each comment is about before answering it. A comment that says something is missing is checked against the manuscript first: if it is there and the reviewer missed it, the reply says where, and the right change is usually to make it easier to find.
4. If the project already has a revision plan or a response template, work from it.

## Splitting the comments

5. Split the comments into numbered points, keeping each source's own order: Editor (E.1, E.2), Reviewer 1 (1.1, 1.2), Reviewer 2, and so on. A paragraph that raises three things becomes three points. Leave nothing out, including praise that asks for nothing (acknowledge it in one line) and minor or typographical points (answer them in a compact list at the end of that reviewer's section).
6. Quote each point in full, or restate it closely when it is long, before the reply. Do not soften or rephrase a criticism into something easier to answer.

## Deciding each reply

7. For every point decide, with the collaborator where it is a judgment call, which of these it is:
   - a change to the manuscript;
   - a clarification without a change (rare: if one reviewer misread it, a reader may too, so prefer a small change);
   - a partial change, saying which part was done and why the rest was not;
   - a reasoned disagreement, backed by an argument, data in the manuscript or a citation, and stated once without repeating it.
8. Do not concede a scientific point the authors have not agreed to concede, and do not promise experiments, analyses or data that do not exist. A new result quoted in a reply must come from the collaborator or the project; mark any number you were not given as a placeholder.
9. Where a requested analysis was not done, say so and say why (not feasible, outside the scope, would not change the conclusion), and consider naming it as a limitation in the manuscript.
10. Where two reviewers ask for opposite things, say so in both replies, state which way the authors went and why, and flag it for the collaborator: it is their decision, and often worth a line to the editor.
11. A citation a reviewer asks for is added only if the collaborator agrees it is relevant. Check that it exists with bib_lookup before putting it in the bibliography.

## Writing each reply

12. Each reply stands alone: what was done, then where. Give the location as section plus page or line if the collaborator's template shows them, otherwise section and paragraph; take line numbers from the compiled revised manuscript, not the old one, and add them last since they move with every edit.
13. Quote the revised or added sentence when it is short; for a long change describe it and point to its location. The quoted text must match the manuscript exactly: copy it, do not retype it from memory.
14. Thank each reviewer once at the top of their section, not in every point. No flattery, no defensiveness, no remarks about the reviewer's competence or motives.
15. Open with a short note to the editor: thanks, a three to five line summary of the main changes, and how changes are marked in the manuscript.

## Manuscript changes

16. When a reply depends on a manuscript change that is not made yet, list that change for the collaborator and offer to make it. Apply changes only when asked, and keep them reviewable. Use `mark-changes` if the journal wants the changes highlighted.
17. After the manuscript changes are in, check the letter against the manuscript: every "we have added" is really there, every quoted sentence matches, and every cross-reference in the letter points to the right place.

## Output

18. Put the response in its own file (ask for the preferred name; response.tex beside the main file is a reasonable default) and compile if it is LaTeX. Reuse the project's existing response template if there is one. Otherwise set the reviewer's text apart from the reply visibly (a quote environment or a coloured box for the comment, plain text for the reply, a third style for quoted manuscript text) and define those as macros once at the top.
19. Finish with a list for the collaborator: points still awaiting their decision, placeholders to fill, changes promised in the letter but not yet made, and reviewer contradictions.

Tone: factual and courteous. The letter is read by an editor deciding whether the concerns were met, so the fastest way to find what changed is what matters most.
