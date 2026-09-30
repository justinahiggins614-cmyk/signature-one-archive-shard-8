# signature-one-archive-shard-8

Frozen storage shard for Manon's Signature Spec Catalog (Pending Patents).

- Holds spec chunks `data/volumes/specs-c01181.jsonl.gz` … `specs-c01299.jsonl.gz`
  (JAH-SPEC-177001 … JAH-SPEC-194850 — 17850 original draft specs).
- Served to the main catalog page at
  https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html
  via its `data/index/shards.json` registry (lazy-loaded on demand).
- FROZEN: never write new chunks here; new drip chunks always land in the main repo.
