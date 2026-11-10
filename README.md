# TCR-8821 — Terminal Corridor Registry

Classification directory for the Northsound Freight Alliance container
terminal network, maintained by the Alliance Data Office.

## Machine-readable index
`registry/manifest.json` is the authoritative index. Its `active_edition`
field identifies the edition that is in force for the current reporting year.
Per-site assignments live in `registry/<edition>.csv` with the columns
`site_code,corridor_code`.

## Editions
| Edition | Status | Published |
|---------|--------|-----------|
| NX-2026.1 | Current | 2026-01-08 |
| NX-2025.4 | Superseded (interim) | 2025-04-02 |
| NX-2024.3 | Superseded (legacy boundaries) | 2024-03-14 |

## Working drafts and review threads
Quarterly working drafts, reviewer threads and older analyses are kept in the
repository's **Issues** tab.
