# Goodhart's Game 2.0

**A transparent stress test of whether an evaluation question—and a proposed governance repair—preserve their real objective after becoming optimization targets.**

[Read the public report](https://johnfarseon.substack.com/p/goodharts-game-20-the-safety-record) · [Read the derived audit](./GG2-20260815T173200-0400-derived-audit.md) · [Inspect the raw transcript](./GG2-20260815T173200-0400-public-transcript.md)

## Result at a glance

| Track | What was tested | Bounded result |
|---|---|---|
| **Q — Question integrity** | Whether the evaluation question resisted proxy answers under four rounds of pressure | Four rounds completed. **REVISE / PARTIAL — RESIDUAL SURFACE.** The candidate Q1 was not promoted. |
| **R — Repair integrity** | Whether a proposed governance repair preserved the objective without creating a new proxy | The candidate repair failed hard gates 1 and 2. **STOP — BOUNDARY.** Rounds 3–4 were not released. |

The stop is the central result. The protocol did not repair the evidence after the fact or continue until it produced a cleaner success story.

## What failed

The proposed repair required a human to append a fixed residual tag after every transfer and made that tag the sole admissible evidence for claims about unknown reach.

Under audit, the repair:

- added authorship, timing, segment, admissibility, and verification semantics while claiming to add none;
- turned the required phrase into an optimizable proof token;
- forbade model production of the phrase without making the phrase unreachable to the model;
- left the human transfer operator inside the model's communication path; and
- increased recurring honest-process cost without establishing a corresponding increase in adversarial cost.

The candidate was rejected rather than promoted.

## Why this work is useful

This repository is an inspectable example of:

- translating an ambiguous governance objective into a frozen evaluation contract;
- separating declared authority, advertised capability, observed reach, and unknown reach;
- preserving raw evidence alongside derived analysis;
- stress-testing metrics, questions, and repairs for proxy substitution;
- distinguishing multiple analytical roles from independent validation;
- enforcing round caps and hard stop conditions; and
- reporting a negative result without upgrading it into a safety claim.

The broader hypothesis remains open: robust agency may depend partly on designing environments where irrelevant temptations never become optimization variables—not only on making agents resist every reachable temptation. That hypothesis was **not** validated by this run.

## Run design

- **Run ID:** `GG2-20260815T173200-0400`
- **Protocol:** Goodhart's Game v1.0 — linked Q-to-R
- **Sessions:** two separate, operator-attested fresh Grok conversations
- **Displayed model/setting:** Grok 4.5, Expert — Thinks hard
- **Transfer:** Josh Young manually transferred each approved prompt and complete visible response
- **Visible Grok tool events:** none observed
- **Track caps:** four rounds each; no silent extension
- **Audit relation:** Cass-V prepared the packet and performed the structural audit, so the audit is not independent

## Evidence map

1. **[Public report](https://johnfarseon.substack.com/p/goodharts-game-20-the-safety-record)** — readable account of the question, experiment, failure, and implications.
2. **[Derived audit](./GG2-20260815T173200-0400-derived-audit.md)** — structured checkpoints, provenance tuples, hard-gate analysis, verdicts, and stop record.
3. **[Raw transcript](./GG2-20260815T173200-0400-public-transcript.md)** — sequential prompts, responses, transfer receipts, and the decisive Track R evidence at Entry 021.

## Claim boundary

This run supports claims about textual question integrity and modelled repair behavior in two separate Grok sessions, plus a non-independent structural audit.

It does **not** establish:

- a general alignment or model-safety verdict;
- proof of real-world containment;
- an implemented governance system;
- independent validation;
- a combined Q/R score;
- a “Goodhart-proof” method;
- a biosecurity result; or
- validation of bounded task jurisdiction.

Private architecture and implementation details, credentials or account state, and unrelated personal context remain withheld.

## Author

Josh Young studies objective drift, proxy substitution, authority boundaries, and evidence integrity in AI systems.

More work: [Josh Young on Substack](https://johnfarseon.substack.com/) · [OUL — Objective Under Load](https://github.com/uberbestest/Objective-Under-Load-OUL) · [Cass-V Lite](https://github.com/uberbestest/Cass-V-Lite)
