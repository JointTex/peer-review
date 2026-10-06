---
name: self-review
description: Review your own manuscript the way a critical referee would before submission, and list the objections worth fixing first.
---

Use this before submission, when the collaborator wants to know what reviewers are likely to object to.

1. Ask for the target venue and article type, and for its review criteria or reviewer guidelines if they are public (read them with fetch_url when given an address). Without them, review against soundness, significance, originality and clarity, and say so.
2. Read the whole manuscript as compiled, not only the source: read_pdf on the output, the figures, the tables and the supplement. Reviewers see the PDF.
3. State in a few sentences what the paper claims and what evidence it gives for each claim. If this is hard to do from the abstract and introduction alone, that is the first finding.
4. Look for what a referee would attack:
   - a claim in the abstract, introduction or conclusion that the results do not support, or support only in part;
   - a missing comparison, control, baseline or ablation that the main claim depends on;
   - results without uncertainty, a single run or a single dataset where variation matters, selection of favourable cases;
   - a method described too thinly to repeat, or settings that differ between the compared methods;
   - numbers that disagree between text, tables and figures; figures that cannot be read at printed size; captions that do not say what is shown;
   - an alternative explanation of the main result that is not discussed;
   - limitations that are absent or only decorative;
   - closely related work that is not cited or not compared with. Look for it with bib_lookup, and with web_search when offered; report only work you verified exists, with its source, and never invent a reference;
   - statements of novelty (first, novel, state of the art) that the related work section does not back.
5. Check what an editor checks before sending it out: scope, length and format against the venue's rules if you have them, anonymisation for blind review (author names, acknowledgements, self-citations in the first person, file metadata, repository links), and required statements. For a full format pass use a submission checklist skill if one is installed.
6. Report as a referee would, but for the authors' eyes:
   - a one-paragraph summary of the paper as a reviewer would describe it;
   - the major objections, most damaging first, each with its location, why a reviewer would raise it, and the smallest change that answers it (a rewrite, a caveat, an analysis of data already in hand, or new work);
   - minor points, briefly;
   - what a reviewer is likely to praise, so it is not cut by accident.
7. Sort the objections by what they cost to answer: fixable in the text now, needs an analysis of existing data, needs new work. Do not recommend overclaiming or hiding a weakness as a fix; the fix for an unsupported claim is to support it or narrow it.
8. Say what you could not judge (a proof not followed, a field-specific convention, data you did not see). Do not predict acceptance or a score.
9. Change nothing in the manuscript during the review. Offer to make the agreed fixes afterwards, as reviewable edits.
