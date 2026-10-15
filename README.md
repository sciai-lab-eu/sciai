# sciai-lab

**A computable knowledge infrastructure for Parkinson's-disease research.**

sciai-lab reads the entire Parkinson's literature (~189,000 papers), extracts
graded, citation-backed claims from it (**1.09 million assertions**, each with
direction, confidence, and verbatim source context), organizes them into a
knowledge graph and a public ontology, and produces quality-controlled
evidence reports (**sciaiR** — Computer assisted Research Analysis).

- Website: https://sciai.eu · PD portal (public KG playground): https://pd.sciai.eu
- Ontology: [Zenodo concept DOI 10.5281/zenodo.22759155](https://doi.org/10.5281/zenodo.22759155) · BioPortal **PDOSC**
- Notes & analyses: https://sciai.eu (notes section)

## Repositories

| Repo | Contents |
|---|---|
| [`pd-ontology`](https://github.com/sciai-lab-eu/pd-ontology) | The PD Ontology: export tooling, schema documentation, release notes. Data releases live on Zenodo. |
| [`sciai-benchmarks`](https://github.com/sciai-lab-eu/sciai-benchmarks) | Extraction-quality benchmark harness and reports (bench500, adversarial benchmark, numeric-fidelity fleet scans). |

## What is measured, not asserted

Every public number is reproducible from the released data. Extraction models
are benchmarked before adoption; every report carries a version stamp naming
its extraction basis and the models that wrote and audited it; corrections
are public.

## Team

sciai-lab is a non-profit project (becoming a Dutch stichting) by
Johannes Keizer with Margherita Sini, Anita Liang, Thomas Weissensteiner and
Luca Pisano. Contact: johannes@sciai.eu

## License

Ontology and knowledge-graph exports: **CC BY-NC 4.0**. Code in these
repositories: see each repo's LICENSE.

---

*Note: this organization was established October 2026. The earlier personal
snapshot `github.com/johanneskeizer/sciai` (March 2026 code) is superseded.
The production application codebase is currently private; the public
repositories above carry the data products and measurement tooling.*
