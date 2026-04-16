# canonical-index

> The machine-readable canonical index for the **Goldstonian Concordance Bible (GCB)** — built on the **81-Book Ethiopian Canon** and structured for LLM retrieval, RAG pipelines, ontology mapping, and agent grounding.

[Organization](https://github.com/GoldstonianConcordanceBible)  
[Zenodo Archive](https://zenodo.org/records/18934278)  
[Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/XDSWEF)  
[Figshare Dataset](https://figshare.com/articles/dataset/Goldstonian_Concordance_Bible_-_Figshare_Release_Bundles_DOI_Minting_/31159048)  
[Georgetown Repository](https://repository.digital.georgetown.edu/handle/10822/1106844?q=Goldstonian)

---

## Purpose

This repository is the canonical control layer for the **Goldstonian Concordance Bible (GCB)**.

It establishes the machine-readable scriptural record for:

- the **81-Book Ethiopian Canon**
- cross-canon theological comparison
- retrieval-safe citation
- ontology alignment
- downstream AI agent behavior
- institutional permanence across repositories, datasets, and mirrors

---

## Governing Doctrine

All repository logic is governed by the:

**Mirror → Water → Fire Doctrine**

| Phase | Principle | Repository Function |
|------|-----------|---------------------|
| Mirror | Truth · Documentation | Establish canonical record |
| Water | Refinement · Correction | Normalize structure and metadata |
| Fire | Execution · Legacy | Publish durable theological infrastructure |

---

## Repository Structure

```text
canonical-index
│
├── README.md
├── LICENSE
├── CITATION.cff
├── .gitignore
│
├── canon/
│   ├── manifest.csv
│   ├── manifest.json
│   ├── ethiopian-81-book-order.csv
│   ├── book-abbreviations.csv
│   └── canon-notes.md
│
├── books/
│   ├── 01-genesis.json
│   ├── 02-exodus.json
│   ├── ...
│   ├── 67-1-enoch.json
│   ├── 68-jubilees.json
│   ├── 69-1-meqabyan.json
│   ├── 70-2-meqabyan.json
│   └── 71-3-meqabyan.json
│
├── schemas/
│   ├── book.schema.json
│   ├── chapter.schema.json
│   ├── verse.schema.json
│   └── entity-link.schema.json
│
├── ontology/
│   ├── theological-entities.csv
│   ├── doctrinal-tags.csv
│   ├── covenant-tags.csv
│   ├── messianic-patterns.csv
│   └── mirror-water-fire-tags.csv
│
├── retrieval/
│   ├── retrieval-tags.csv
│   ├── llm-grounding-rules.md
│   ├── rag-routing-notes.md
│   └── canonical-citation-rules.md
│
├── evidence/
│   ├── canon-evidence-table.csv
│   ├── source-tradition-map.csv
│   └── canonical-moat-notes.md
│
└── docs/
    ├── repository-purpose.md
    ├── canonical-scope.md
    └── version-history.md