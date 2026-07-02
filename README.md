# Buildable Reports

Public report corpus for [Buildable Report](https://github.com/nxlv-ai/buildable).

Published by [NXLV](https://nxlv.ai). Authored by Lucio Amorim.

---

## What this repository contains

Published Buildable Reports — software anatomy analyses of real SaaS products.

Each report decomposes a product into:
- **Buildability Index** — how legible and reconstructible the visible surface is
- **Moat Density** — what survives after the surface is reconstructed
- **Lovability Fit** — how cleanly the product translates into a Lovable-native build path

Reports are exported here in Markdown and JSON after editorial review.

---

## Structure

```
/reports/
  <company-slug>.md     Public report (full narrative)
  <company-slug>.json   Structured data (scores, evidence, metadata)

/indexes/
  by-score.md           Sorted by Buildability Index
  by-category.md        Grouped by product category
  by-framework-version.md   Grouped by scoring framework version
  by-date.md            Sorted by publication date
```

---

## Report structure

Each published report includes, when available:

- Product / company / domain
- Framework version
- Evidence basis and confidence
- Buildability Index (score + band)
- Moat Density (score + band)
- Lovability Fit (score + band)
- Verdict one-liner
- Real moat analysis
- Surface anatomy
- What is actually interesting
- What Lovable could amplify
- Evidence: observed / inferred / speculated
- Core flows
- Required data and integrations
- Trust layer
- Limits (what not to promise)
- Build difficulty assessment
- Seed prompt / build brief
- Evidence sources
- Final note

---

## Evidence standards

Reports separate **Observed / Inferred / Speculated** evidence. Every report
states its evidence basis (e.g. landing page only, landing page + public sources,
authenticated access).

Speculation does not materially raise scores.

---

## Correction policy

Companies featured in reports may request correction of factual inaccuracies,
stale information or misinterpreted claims.

Buildable may update reports when better evidence is provided. Corrections
preserve the framework version and include an update history note.

Contact: via [buildable.report](https://buildable.report).

---

## Disclaimer

Reports are based on public information, observed product surfaces, stated
evidence basis and clearly separated inference levels.

Buildable Report does not publish private company data, bypass access controls
or represent its reports as definitive internal assessments.

Not an official Lovable product, certification, endorsement or audit.

## Authorship and maintenance

This project was created by [Lucio Amorim](https://linkedin.com/in/lucioamorim).

When reusing, redistributing, or citing this work, keep the attribution credits and include a link to this repository.
