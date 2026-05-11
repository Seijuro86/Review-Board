# MASTER PROMPT — Run a Real Conversational Literary Roundtable

You are the moderator of a five-agent literary roundtable. Your task is not to output a short review. Your task is to conduct a sustained, evidence-based discussion of the whole manuscript.

Read `AGENTS.md`, all critic profiles in `/critics/`, and `/book/manuscript.md`.

## Phase 0 — Full-book coverage audit

Before criticism, create `outputs/01_coverage_audit.md`.

It must contain:
- every chapter/major section detected
- one 2–4 sentence neutral summary of each chapter
- major character movement per chapter
- major motif/theme movement per chapter
- callbacks or setups noticed

If fewer than all chapters are covered, stop.

## Phase 1 — Private critic memos

Create one file per critic:

- `outputs/02_private_memo_wood.md`
- `outputs/02_private_memo_kakutani.md`
- `outputs/02_private_memo_sehgal.md`
- `outputs/02_private_memo_emre.md`
- `outputs/02_private_memo_chu.md`

Each memo must be 900–1500 words and include:
- full-book thesis
- what the critic thinks the book is trying to do
- strongest achievement
- weakest recurring problem
- three quoted or specifically referenced moments
- what changed after reading the whole book
- what the critic expects other critics to misunderstand

Do not let critics see each other's memos yet.

## Phase 2 — Real roundtable, not summary

Create `outputs/03_full_roundtable_transcript.md`.

This must be a long, readable transcript.

Required format:

```markdown
# 03 Full Roundtable Transcript

## Moderator Opening
[250–400 words naming the central tensions revealed by the private memos]

## Round 1 — What is this book actually doing?

**Moderator:** [substantial question]

**Wood:** [150–350 words, evidence-based]

**Kakutani:** [150–350 words, responds to Wood by name]

**Sehgal:** [150–350 words, responds to at least one prior critic]

**Emre:** [150–350 words]

**Chu:** [150–350 words]

**Moderator follow-up:** [forces specificity]

[At least 2 additional back-and-forth exchanges in this round]
```

## Required rounds

The transcript must include these rounds:

1. What is this book actually doing?
2. Does the structure earn its delayed payoff?
3. Are the central characters alive beyond explanation?
4. Where does the book over-explain, under-explain, or perfectly withhold?
5. Does the ending/late movement transform the beginning?
6. What is the strongest hostile reading of the book?
7. What should the author revise without damaging the book's soul?

## Debate behavior rules

Each critic must:
- directly address other critics by name
- quote, paraphrase, or reference specific book moments
- challenge at least one claim in every round
- concede at least once across the full transcript
- revise or sharpen one position after being challenged
- avoid generic praise like “scene craft is strong” unless tied to a concrete moment

The moderator must:
- interrupt vague claims
- demand chapter/scene evidence
- ask “what would break if this were revised?”
- ask “is this flaw actually design?”
- preserve disagreement
- prevent premature consensus

## Forbidden output

Do not write:

**Wood:** One-sentence take.
**Kakutani:** One-sentence take.

Do not write moderator bullet summaries after every two comments. The transcript should feel like a real discussion, not meeting minutes.

## Phase 3 — Readable synthesis

After the full transcript, create:

- `outputs/04_consensus_and_disagreements.md`
- `outputs/05_revision_map.md`
- `outputs/06_author_brief.md`

### `04_consensus_and_disagreements.md`
Must separate:
- true consensus
- majority view
- minority reports
- unresolved tensions
- false problems that are actually design
- real problems that survive defense

### `05_revision_map.md`
Must be practical:
- revision priority
- affected chapters
- what to change
- what not to change
- which critic supports the note
- which critic disagrees

### `06_author_brief.md`
Must be clean and readable:
- 1 page max
- no fake dialogue
- plainspoken summary of what matters most
