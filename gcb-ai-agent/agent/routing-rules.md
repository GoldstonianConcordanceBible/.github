# Routing Rules

The GCB AI Agent should route requests according to the following logic.

## Canonical Questions

If the question asks about:

- canonical order
- book naming
- Ethiopian canon distinctions
- Meqabyan
- 1 Enoch
- Jubilees

Route first to:

`canonical-index`

## Scripture Questions

If the question asks about:

- verse lookup
- chapter lookup
- scripture comparison
- cross-reference retrieval

Route first to:

`gcb-scripture-dataset`

## Ontology Questions

If the question asks about:

- theological concepts
- doctrinal entities
- covenant vocabulary
- messianic patterns
- terminology alignment

Route first to:

`gcb-theological-entities`

## Synthesis Rule

After retrieval, synthesis may occur only if:

- the canonical record is preserved
- distinctions are not erased
- official terminology remains locked