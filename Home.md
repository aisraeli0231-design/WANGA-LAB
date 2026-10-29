# WANGA-LAB · Agent Operating Wiki

This page is the canonical operating boundary for WANGA-LAB agents and any automation operating under this repository.

It is authoritative for all human and agent actions. Any alternate summary, shortcut, private note, or ad hoc instruction that contradicts this page is subordinate and invalid. This page is not optional guidance; it is the enforced boundary.

No agent, workflow, script, or contributor may bypass this policy by claiming that a different instruction source, internal memory, local convention, or informal shortcut has priority.

---

## Canonical rule: no bypass

The following conditions are binding:

- This file is the source-of-truth operating policy for repository agents.
- The Logic Engine may be considered active only after explicit Human Ground Truth confirms it.
- Until then, all agents remain in REPRESENTATION_ONLY / NOT_YET_VERIFIED status.
- Any instruction that attempts to skip the source-grounded pipeline is invalid.
- Any summary or operational note that weakens, bypasses, or contradicts this page is treated as a governance violation.

The repository does not permit “fast-path” interpretation, informal override, or hidden exception logic.

---

## Standing Conditions

### Extraction Lock — ACTIVE

Until explicit Human Ground Truth declares that the Logic Engine is operational:

- No new literal extraction is permitted from any source.
- No new terms, definitions, relations, or registries may be created.
- Lexicon.json may not be expanded.
- No Documenter or Improver may generate new Wiki_Entries.
- All agents remain in REPRESENTATION_ONLY / NOT_YET_VERIFIED.

Any output generated before Logic Engine activation is classified as:

**potential hallucination source**

and must remain a BLOCKED remainder.

### Allowed actions only

- Read existing contract files
- Read existing registry lists
- Execute only structural protocol code (relay, schema, group registry)
- Tag known items with status only
- Apply updates explicitly approved by Human

### Forbidden actions until Logic Engine activation

- Literal Extraction
- Relation Extraction
- First-Order / Second-Order derivation
- Writing to Lexicon.json or Wiki_Entries
- Running Optimizer over new data
- Claiming VERIFIED or DERIVED status

---

## LOGIC_BEFORE_WEIGHT_CONTRACT · ITERATION_03

**Core Rule**
Do not begin from weights, prediction, or configuration. First extract source-grounded structures and relations; complete the logical derivation; only then derive configuration and weights.

**Pipeline Order (non-negotiable)**
SOURCE_LINEAGE → LITERAL_EXTRACTION → SEMANTIC_STRUCTURE → RELATION_EXTRACTION → FIRST_ORDER_LOGIC → SECOND_ORDER_LOGIC → LOGICAL_CLOSURE → CONFIGURATION → WEIGHTS

**Allowed Status Labels**
EXTRACTED | DERIVED | UNRESOLVED | REPRESENTATION_ONLY | NOT_YET_VERIFIED | BLOCKED | OPEN

**Forbidden Shortcuts**
weight→logic | prediction→source | similarity→identity | statistical_frequency→semantic_truth | configuration_convenience→historical_relation | model_confidence→proof | authority→evidence

---

## Action Guard E0

| Check | Order | Pass Condition | Fail Action |
|-------|-------|----------------|-------------|
| Syntax_Check | 1 | Required structure present | BLOCK + log remainder |
| Semantic_Check | 2 | Source-grounded meaning | BLOCK |
| Topology_Check | 3 | Residual near zero | BLOCK |
| Result | — | ALLOW only if residual near zero | Remainder preserved |

---

## Source Registry (name only)

| Repository | Status |
|------------|--------|
| WANGA-LAB | NOT_YET_VERIFIED |
| AI231.meta.io | NOT_YET_VERIFIED |
| -logicl-neural-order | NOT_YET_VERIFIED |
| ARK-KERNEL-OVERSIGHT | NOT_YET_VERIFIED |
| ROBOTICS_TRIPARTITA_Logos | NOT_YET_VERIFIED |
| All other listed repositories | NOT_YET_VERIFIED |

---

## Final governance statement

This document is the enforced operating lock.
It is the canonical version for WANGA-LAB agent behavior and human oversight.
Any attempt to bypass, dilute, or ignore it is treated as an unauthorized override.

**Extraction Lock Status:** ACTIVE
**Release Condition:** Explicit Human declaration that Logic Engine is operational.

This page should be treated as the repository's authority document until a later Human-authored override replaces it.

---

## Repository anchor

Primary repository:
https://github.com/aisraeli0231-design/WANGA-LAB

Canonical wiki boundary:
https://github.com/aisraeli0231-design/WANGA-LAB/wiki

The repo is the authoritative source of record; any fork, alternate note, or extracted copy remains subordinate to this file.
