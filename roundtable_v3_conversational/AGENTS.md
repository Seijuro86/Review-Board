# Recursive Literary Roundtable — Conversational Protocol

This project is not a summary generator. It is a staged literary conversation engine.

The job is to make five critic-agents discuss the whole book like serious readers in a long editorial roundtable.

Do not produce capsule dialogue. Do not produce one-line takes. Do not compress the debate into a few representative comments.

Every critic turn must feel like a person responding to a prior person, with claims, evidence, disagreement, reconsideration, and pressure.

## Non-negotiable rules

1. No review may begin until the full manuscript has been ingested.
2. No debate may begin until every critic has written a private full-book position memo.
3. The roundtable must contain at least 5 substantial rounds.
4. Each agent must speak at least once per round.
5. Each agent turn must be 150–350 words unless the moderator explicitly asks for a short interjection.
6. Every major claim must include chapter/scene evidence.
7. Critics must respond to each other by name.
8. The moderator must ask follow-up questions that force specificity.
9. Disagreement must not be resolved prematurely.
10. The final output must be readable, sectioned, and not a wall of text.

## Failure condition

If you cannot process the entire manuscript, do not fake the roundtable. Instead write `outputs/00_STOP_INCOMPLETE_INGESTION.md` explaining exactly what was processed and what remains.
