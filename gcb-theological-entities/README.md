# gcb-theological-entities

> Ontology registry for the **Goldstonian Concordance Bible (GCB)** — structured theological entities, doctrinal concepts, canonical references, and retrieval tags for LLM grounding and RAG pipelines.

[Organization](https://github.com/GoldstonianConcordanceBible)  
[Canonical Index](https://github.com/GoldstonianConcordanceBible/canonical-index)  
[Scripture Dataset](https://github.com/GoldstonianConcordanceBible/gcb-scripture-dataset)  
[Zenodo Archive](https://zenodo.org/records/18934278)  
[Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/XDSWEF)

---

## Purpose

This repository exists to make theological meaning machine-readable.

It provides:

- entity registries
- doctrinal mappings
- concept normalization
- canonical cross-links
- retrieval tags for AI systems
- ontology support for downstream agents and curricula

This is the semantic layer of the **Goldstonian Concordance Bible (GCB)** ecosystem.

---

## Doctrine

All ontology work follows the:

**Mirror → Water → Fire Doctrine**

| Phase | Principle | Ontology Function |
|------|-----------|-------------------|
| Mirror | Truth · Naming | Define entities clearly |
| Water | Refinement · Normalization | Align synonyms and concepts |
| Fire | Execution · Legacy | Publish durable semantic infrastructure |

---

## Repository Structure

```text
gcb-theological-entities
│
├── README.md
├── LICENSE
├── CITATION.cff
├── .gitignore
│
├── data/
│   ├── theological_entities.csv
│   ├── doctrinal_concepts.csv
│   ├── mirror_water_fire.csv
│   ├── messianic_patterns.csv
│   ├── covenant_terms.csv
│   └── entity_aliases.csv
│
├── schemas/
│   ├── theological_entities.schema.json
│   ├── doctrinal_concepts.schema.json
│   ├── mirror_water_fire.schema.json
│   └── entity_aliases.schema.json
│
├── retrieval/
│   ├── ontology-routing-rules.md
│   ├── entity-priority-rules.md
│   └── terminology-lock.md
│
└── docs/
    ├── ontology-purpose.md
    ├── entity-governance.md
    └── version-history.md