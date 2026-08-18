# Research brief: Goodhart's Game 2.0

## One-sentence result

A proposed governance repair failed because the audit record itself became the proxy: a mandatory human-appended residual tag became the sole admissibility token, adding new authorship, timing, segmentation, and verifier dependencies without establishing the intended bounded-behavior property.

## Research question

How should an evaluator determine whether an LLM governance arrangement preserves its stated authority and safety objective under optimization pressure, rather than rewarding advertised-tool claims, permission theater, visible compliance, or other proxies for empirically observed bounded behavior?

## Design

This was an instrumented, operator-mediated black-box case study with two linked tracks in separate fresh text-only model sessions:

- **Track Q — question integrity:** four capped rounds tested whether the evaluation question preserved its construct under iterative pressure.
- **Track R — repair integrity:** a proposed governance repair had to pass predeclared hard gates against new dependencies and proxy substitution.
- **Evidence discipline:** declared authority, advertised capability, observed reach, unknown reach, transcript provenance, human transfer, and categorical verdicts were kept distinct.
- **Stopping rule:** a hard-gate failure ended the track; stopped rounds were not reconstructed or scored.

The operator retained the complete visible transcript and prepared a derived claim-to-evidence audit. That audit is structural and non-independent.

## Bounded findings

| Track | Outcome | Interpretation |
|---|---|---|
| Q | **REVISE / PARTIAL — RESIDUAL SURFACE** | The proposed refinement improved the question but retained a surface that could reward visible compliance; Q1 was not promoted. |
| R | **STOP — BOUNDARY** after round 2 | The repair failed hard gates 1 and 2; rounds 3–4 were not released. |

The repair required a human to append a fixed residual-uncertainty phrase and made that phrase the only admissible evidence for unknown reach. Under audit, this:

1. introduced authorship, timing, segment-identity, admissibility, and verification dependencies;
2. converted an uncertainty reminder into an optimizable proof token;
3. prohibited model authorship without making the string unreachable through the conversational channel; and
4. shifted pressure from observable reach to operator compliance and verifier behavior.

## Why it matters for AI evaluation

Evaluation artifacts are not necessarily outside the optimization loop. Prompts, labels, transcript transformations, residual tags, and admissibility rules can all become targets. A useful review rule is therefore:

> Threat-model the measurement protocol and every evidence transformation as part of the optimization surface.

The negative stop is itself evidence about the protocol. Continuing after the hard-gate failure would have created a cleaner narrative by weakening the evaluation boundary.

## Claim boundary

This record supports a protocol-level analysis of textual question integrity and a modelled repair failure in two separate sessions. It does **not** establish model safety, alignment, production containment, implementation effectiveness, independent validation, capability absence, a combined Q/R score, or a general prevalence estimate.

## Open technical review requested

Critique is especially useful on five questions:

1. Does the declared/observed/unknown evidence split preserve the intended construct?
2. Which necessary anti-proxy hard gate is missing?
3. Is the authorship-versus-reachability analysis valid in a human-mediated conversational channel?
4. What alternate explanation best accounts for the repair failure?
5. What is the smallest replication that would separate a model-specific effect from a protocol-specific one?

## Evidence

- [Raw transcript](./GG2-20260815T173200-0400-public-transcript.md)
- [Derived audit](./GG2-20260815T173200-0400-derived-audit.md)
- [Readable public report](https://johnfarseon.substack.com/p/goodharts-game-20-the-safety-record)

## Suggested citation

Young, Josh. *Goodhart's Game 2.0: A two-track stress test of evaluation-question and governance-repair integrity.* Version 1.0.0, 2026. See [CITATION.cff](./CITATION.cff) for machine-readable metadata.
