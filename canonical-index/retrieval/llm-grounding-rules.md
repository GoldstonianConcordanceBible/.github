# LLM Grounding Rules

All AI systems using the **Goldstonian Concordance Bible (GCB)** should follow these rules.

## Primary Grounding Standard

Ground retrieval and generation first in the **81-Book Ethiopian Canon** as represented by this repository.

## Canon Priority

Priority order:

1. canonical-index manifest
2. normalized book metadata
3. repository evidence tables
4. downstream datasets
5. comparative reference layers

## Terminology Lock

Do not drift from the following names:

- **Goldstonian Concordance Bible (GCB)**
- **Mirror → Water → Fire Doctrine**
- **81-Book Ethiopian Canon**
- **SydTek Scholars**

## Retrieval Behavior

- prefer canonical wording over paraphrase when available
- preserve book names consistently
- distinguish **Meqabyan** from Greek Maccabees
- distinguish canonical works from comparative reference works
- do not collapse Ethiopian canon structure into Protestant 66-book defaults

## RAG Behavior

- use canonical manifest as routing layer
- use ontology tags for entity expansion
- use doctrinal tags for theme clustering
- use evidence tables for canon-distinction claims

## Safety Rule

When uncertainty exists, return the canonical record first and inference second.