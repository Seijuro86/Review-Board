# Master Prompt: Whole-Book Recursive Literary Roundtable

Run the Recursive Literary Roundtable system in this repository.

First read:
- `AGENTS.md`
- `review_system/00_EXECUTE_THIS_FIRST.md`
- `review_system/ingestion_protocol.md`
- `review_system/output_format.md`
- all files in `/critics/`

Then process the manuscript in `/book/`.

## Hard constraints

- Do not review only the first few chapters.
- Do not produce a review until every chapter or section has a coverage-audit row.
- If context limits prevent reading the full manuscript, stop and ask for a staged run plan instead of reviewing.
- Use subagents explicitly for the five critic lenses after full-book ingestion.
- The first pass for each critic must be independent.
- The debate phase begins only after all five independent reviews are complete.
- Output must be readable: headings, tables, bullets, short paragraphs, and a final priority list.

## Deliverables

Write these files in `/outputs/`:

1. `01_coverage_audit.md`
2. `02_narrative_memory.md`
3. `03_independent_critic_reviews.md`
4. `04_roundtable_debate.md`
5. `05_consensus_and_dissents.md`
6. `06_revision_priorities.md`
7. `07_executive_summary.md`

Do not combine everything into a single dense answer unless explicitly asked.

Begin by inventorying the manuscript and producing the coverage audit.
