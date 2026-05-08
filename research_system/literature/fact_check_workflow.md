# Fact Check Workflow

## Purpose

Protect the knowledge base from inaccurate, incomplete, or overconfident claims.

## Non-Negotiable Rules

1. No metric enters the knowledge map as fact unless it has a source in `evidence_register.md`.
2. A DOI alone is not enough for a quantitative claim. The checked source must contain the specific value.
3. Abstract-only values are allowed for scouting, not for final route selection or manuscript claims.
4. If a paper is paywalled, mark unknown details as `Need full text`; do not infer methods or conditions.
5. Always record RH, temperature, membrane thickness, and test direction for conductivity when available.
6. If two sources conflict, mark the entry `Conflict` and stop using the value until resolved.

## Fact Check Steps

1. Identify the claim.
2. Find the primary source: publisher page, DOI landing page, or open full text.
3. Verify bibliographic fields: title, authors, journal, year, DOI.
4. Verify material identity: COF name, polymer/scaffold, additive, proton carrier.
5. Verify conditions for each metric: RH, temperature, thickness, measurement direction, MEA operating conditions.
6. Record evidence level in `evidence_register.md`.
7. Update `literature_matrix.md` only after evidence status is assigned.
8. If the paper is central, create or update a paper note.

## Red Flags

- Conductivity without RH or temperature.
- Fuel-cell power density without gas, humidity, membrane thickness, or catalyst loading.
- "High stability" without duration and test condition.
- Acid-loaded membranes without leaching/soaking evidence.
- COF composite claims without morphology or dispersion evidence.
- Review articles cited as evidence for a primary experimental value.

## Claim Language

Use:

- "Reported" for values from a paper.
- "Verified from publisher page/full text" only after checking the source.
- "Lead to verify" for unconfirmed entries.
- "Suggests" for mechanism interpretations.

Avoid:

- "Proves" unless controls and conditions are sufficient.
- "Best" unless a benchmark set is defined.
- "Stable" without duration, condition, and retention percentage.
