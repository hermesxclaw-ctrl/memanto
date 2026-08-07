# Round-trip validation report

Generated: 2026-08-07T04:25:06.040092+00:00
Source: Qdrant collection 'memories' (61 records)
Mapped: 61 memories -> 61 re-imported from OKF bundle

## Golden QA (recall parity)

| Question | Expected | Found in bundle |
| --- | --- | --- |
| Where does Tim live? | lisbon | YES |
| What is Tim's cat's name? | pixel | YES |
| What embedding store does the team use? | qdrant | YES |
| What is the preferred backend language? | python | YES |
| What coffee does Tim order? | flat white | YES |

**Recall parity: 5/5 (100%)**

## Artifacts

- `export.json` — raw Qdrant collection dump (provider-style export)
- `mapped_preview.jsonl` — mapped Memanto memory payloads
- `okf_bundle/` — valid OKF bundle (index.md + memories/)