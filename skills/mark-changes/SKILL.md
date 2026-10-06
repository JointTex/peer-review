---
name: mark-changes
description: Mark the revised passages in a LaTeX manuscript for a resubmission, and produce the list of changes with their locations.
---

Use this when a journal asks for a marked-up manuscript or a summary of changes with a revision.

1. Ask what the journal wants: changes highlighted in colour, tracked insertions and deletions, a separate marked copy beside a clean one, or only a list. Read the author guidelines with fetch_url if the collaborator gives the address. Ask whether deleted text has to be shown.
2. Find out what the earlier version is. Use read_changes for what changed in this project, and ask whether the submitted version is kept as a file, a folder or a label in the project history. If there is no earlier version to compare with, mark only the changes the collaborator points to or that you make from here on, and say that the marking is incomplete for anything changed before.
3. Reuse a marking mechanism the project already has (a revision macro, the changes package, an existing colour convention). Otherwise add one small macro in the preamble and tell the collaborator its name, for example a command that colours its argument and a switch that turns the colour off, so the clean and marked copies come from the same source. Check that the colour package is loaded and that the class does not already define the name.
4. Mark at the level of the sentence or clause that changed, not whole sections and not single characters. Things to watch:
   - do not wrap a paragraph break, a sectioning command, a float, a display equation environment or a bibliography entry inside the macro; mark the text inside them, or note the change in the list instead;
   - a changed table cell, caption or equation is marked inside the cell, caption or equation;
   - a new figure or table is flagged in its caption;
   - moved text is marked at its new place and listed as moved;
   - a deletion is shown only when the journal asks for deletions, with a struck-through or margin form that still compiles.
5. Do not change wording while marking. If a passage needs rewriting, that is a separate edit the collaborator asks for.
6. Compile, fix what the marking broke, and look at the result with read_pdf: the marking should be visible, and line and page breaks should not differ so much from the clean copy that the locations cited in the response letter stop matching. If the letter cites line numbers, state which copy they refer to.
7. Produce the list of changes in its own file or as a section of the response letter: location (section, page or line in the revised manuscript), what changed in one line, and the reviewer point it answers when there is one. Changes not asked for by any reviewer are listed too, under their own heading.
8. Say how to produce the clean copy (the switch from step 3), and remind the collaborator to remove or disable the marking before the final accepted version.
