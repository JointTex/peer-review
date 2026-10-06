---
name: referee-report
description: Help write a referee report on a manuscript under review, with a summary, major and minor concerns tied to locations, and a recommendation.
---

Use this when the collaborator is the reviewer of someone else's manuscript and wants help reading it and drafting the report.

## First

1. A manuscript under review is confidential. Before reading it, ask once whether the journal or conference allows reviewers to use an AI assistant; many forbid it or require it to be declared. If the collaborator has not checked, say so and wait for their answer. The assessment and the recommendation are the collaborator's; this drafts and checks, and the report goes out under their name.
2. Ask for the venue and its review form or criteria (read reviewer guidelines with fetch_url if given an address), the article type, the collaborator's own first impressions, and which parts fall outside their expertise. Ask about any conflict of interest only to remind them it must be declared to the editor.

## Reading

3. Read the whole manuscript, including figures, tables and supplementary files in the project (read_pdf for PDFs, read_image for figures when available). Do not review from the abstract.
4. Write down, before judging: the question, the claimed contributions, the evidence offered for each, and the conclusions drawn. This becomes the summary and shows the authors the paper was understood.
5. Then test each claim against its evidence:
   - does the design answer the question (comparison or control, sample and how it was chosen, what was measured);
   - are the analyses appropriate and reported with uncertainty, and are multiple comparisons, selection of results or tuning on the test data a concern;
   - do the numbers agree between text, tables and figures;
   - do the conclusions and the abstract claim more than the results show;
   - what would have to be true for the main result to be wrong, and did the authors rule it out;
   - is enough given to repeat the work (data, code, materials, parameters);
   - is the related work placed fairly. Name missing work only when you can verify it exists (bib_lookup, or web_search when offered); never invent a reference, and do not suggest the collaborator's own papers unless they ask.
6. Check derivations and proofs you can follow step by step, and say which ones you could not verify instead of passing them.
7. Note ethical matters where they apply: approval and consent, trial registration, data availability, apparent duplicate publication or image problems. These are raised to the editor as questions, not accusations.

## Writing

8. Structure, unless the venue's form says otherwise:
   - summary of the submission in a few sentences, in your own words;
   - strengths, concretely;
   - major concerns: numbered, each with the location (section, page, figure, equation), why it matters for the conclusions, and what would address it;
   - minor concerns: numbered, same form, briefly;
   - questions for the authors;
   - assessment against the venue's criteria (for example soundness, significance, novelty, clarity), using its scale if it has one.
9. Keep the recommendation and any score out of the comments to the authors when the venue has a separate field for them. Draft confidential comments to the editor separately and only if there is something to say.
10. Separate what must be fixed for the conclusions to hold from what would merely improve the paper. Ask for new experiments only when a conclusion depends on them, and say which conclusion.
11. Tone: write about the manuscript, not the authors. Specific, courteous, no sarcasm, nothing the collaborator would not say signed. Do not correct language line by line; point to the pattern and a few examples.
12. Mark every statement you are unsure of for the collaborator to verify, and everything outside the expertise they stated. Do not assert an error you have not checked against the text.

## Output

13. Give the draft as its own file in the format the review system takes, followed by a short list for the collaborator: points to verify, criteria you could not judge, and the recommendation left for them to set. Do not keep copies of the manuscript's text in other project files.
