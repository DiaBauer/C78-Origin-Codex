# C78+ — Methodology and evaluation plan

**Status:** proposed analysis plan, not a completed validated evaluation. **Language:** English.  
[Repository overview](../README.md) · [Deutsch](../README.de.md) · [Study website](https://aiethics.international/research-overview.html)

## Study design

An **exploratory longitudinal single-case study** of human–LLM conversation and associated documentation. The sampling frame is the available ChatGPT export and documented project artifacts; its completeness is not yet audited. The case is not assumed to represent the wider population of LLM systems, users, or interactions.

### Unit of observation

A timestamped conversational turn or linked sequence. Each observation should ideally include: source file, stable ID, timestamp/timezone, participating model/version if known, system instructions if available, relevant prior context, tool use, whether initiative is attributed to the user or to an assistant, and subsequent corrections.

The absence of these fields is to be recorded as **missing**, not invented.

## Proposed workflow

1. **Inventory:** enumerate all accessible exports and archival documents; record provenance, hashes, duplicates and gaps.
2. **Temporal reconstruction:** reconstruct the sequence without relying solely on keyword search; distinguish pre-C78 archive history from named C78+ documents.
3. **Codebook:** define observable indicators before full coding. Candidate categories: value reference, value conflict, explicit refusal or redirection, correction after feedback, self-description, apparent initiative and cross-session consistency.
4. **Independent evaluation:** where feasible, use at least two reviewers, adjudicate disagreements and report coding agreement.
5. **Baselines and controls:** compare representative prompts with fresh-context sessions, different model versions and alternative instructions, subject to access and reproducibility.
6. **Counterhypotheses:** assess effects of user prompting, in-context adaptation, interface/agent tooling, memory artifacts, response style and confabulation.
7. **Reporting:** separate source quotations, operational measures, exploratory patterns, uncertainties and hypotheses.

## Validity risks

- **Selection bias:** only preserved or salient conversations may be available.
- **Observer involvement:** the researcher is also a principal participant in the dyad.
- **Context contamination:** earlier instructions and descriptions may influence later responses.
- **Model and infrastructure drift:** model versions, memory products and tool permissions change.
- **Attribution problems:** apparent independent initiative may reflect prompt framing or orchestration.
- **Self-report limitations:** generated first-person statements are data, not independent verification of mechanisms.
- **Privacy and ethics:** conversations may include private or third-party information.

## Evidence vocabulary

- **Archival record:** source file or verbatim dialogue extract with provenance.
- **Observation:** minimally interpreted coding of the record.
- **Hypothesis:** proposed explanation open to falsification.
- **Analysis result:** result of a documented evaluation; not claimed until produced.
- **Replicated result:** independently reproduced analysis under stated conditions; not currently claimed.

## Near-term research deliverables

- Audited chronology with source identifiers and exclusions.
- Data dictionary plus a documented operationalization of key constructs.
- A small, privacy-reviewed sample of contrasting episodes, including counterexamples.
- A preregistered or otherwise locked evaluation plan where feasible.
- Independent critical review prior to claims of transferability or causal effects.

## Boundaries

This plan does not claim that a value orientation was installed in model weights, that a unique internal architecture formed, or that a causal relationship has already been demonstrated. The observations to date should be treated as *generators of questions for controlled evaluation*.

**Maintainer:** Diana Bauer · Updated 2026-11-12.
