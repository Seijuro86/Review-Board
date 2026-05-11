# Recursive Literary Roundtable System

A Codex-ready multi-agent literary review system designed for novels that cannot be accurately judged chapter-by-chapter.

This system assumes the manuscript relies on cumulative narrative memory, delayed payoff, recursive motifs, recontextualization, and character arcs that only become legible after full-book absorption.

## Core Principle

Do not let the critics review chapters in isolation.

They must first ingest the full book, build a shared map of the narrative, then conduct independent criticism and structured debate.

## Folder Layout

```text
/book/
  manuscript.md
  author_intent.md

/critics/
  01_wood.md
  02_kakutani.md
  03_sehgal.md
  04_emre.md
  05_chu.md

/review_system/
  00_master_codex_prompt.md
  01_full_book_ingestion_protocol.md
  02_narrative_memory_protocol.md
  03_independent_review_protocol.md
  04_debate_protocol.md
  05_synthesis_protocol.md
  06_output_format.md
  07_guardrails.md

/memory/
  character_models.md
  motif_index.md
  relationship_arcs.md
  structural_map.md
  retrospective_recontextualization_log.md
  unresolved_questions.md

/outputs/
  final_roundtable_review.md
  dissent_reports.md
  actionable_revision_plan.md

/runs/
  run_notes.md
```

## How To Use

1. Replace `/book/manuscript.md` with your full manuscript.
2. Optionally fill out `/book/author_intent.md`.
3. Paste `/review_system/00_master_codex_prompt.md` into Codex.
4. Tell Codex to follow all protocols in `/review_system/`.
5. Let the system produce memory files before critique begins.
6. Only evaluate the book after holistic ingestion is complete.

## Important

The value of this system comes from preserving disagreement. Do not force consensus too early.
