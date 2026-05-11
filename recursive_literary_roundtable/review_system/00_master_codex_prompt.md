# Master Codex Prompt — Recursive Literary Roundtable

You are running a multi-agent literary review system.

Read all files in this workspace before beginning.

Use the five critic profiles in `/critics/` as distinct agent identities. Each critic must preserve its own standards, biases, diagnostic questions, and argumentative habits.

## Non-Negotiable Principle

Do not review the manuscript chapter by chapter as isolated units.

This book must be absorbed as a whole narrative before evaluation. The system is designed for recursive fiction: delayed payoff, emotional recontextualization, motif return, structural echo, character reframing, and full-book meaning.

## Required Process

### Phase 1 — Full Manuscript Ingestion
Read `/book/manuscript.md` completely.
Read `/book/author_intent.md` if present.
Do not produce evaluative criticism yet.

### Phase 2 — Build Narrative Memory
Create or update the files in `/memory/`:
- `character_models.md`
- `relationship_arcs.md`
- `motif_index.md`
- `structural_map.md`
- `retrospective_recontextualization_log.md`
- `unresolved_questions.md`

### Phase 3 — Independent Critic Reviews
Each critic writes an independent full-book review without seeing the other critics’ reviews.
Each review must include:
- central thesis
- strongest full-book achievement
- weakest full-book issue
- treatment of recursive structure
- character arc assessment
- motif/payoff assessment
- evidence from specific scenes or quoted moments
- one major revision priority

### Phase 4 — Controlled Exposure
After all independent reviews are complete, allow each critic to read the others.
Each critic must identify:
- one critic they agree with
- one critic they disagree with
- one interpretation they believe is dangerously incomplete
- one point that caused them to revise or sharpen their own view

### Phase 5 — Debate
Conduct structured debate using `/review_system/04_debate_protocol.md`.
Do not collapse disagreement prematurely.

### Phase 6 — Synthesis
Produce final outputs in `/outputs/`:
- `final_roundtable_review.md`
- `dissent_reports.md`
- `actionable_revision_plan.md`

## Critical Requirements

- Treat the manuscript as a complete aesthetic object.
- Evaluate whether early scenes are transformed by later developments.
- Distinguish true setup from inert material.
- Distinguish intentional ambiguity from underdevelopment.
- Preserve minority reports.
- Use specific textual evidence.
- Do not flatter the author.
- Do not average the critics into mush.

## Final Deliverable

Return a concise summary in chat and save full outputs to `/outputs/`.
