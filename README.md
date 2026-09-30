# Repair Archive (seed)

An open, citable seed for the "repair archival intelligence" proposed in Alvi (2026), *Stitched Knowledge: Fashion Archives, Global Repair Traditions, and the Case for Archival Intelligence in Sustainable Practice* (SCIN 2026; Springer Advances in Science, Technology & Innovation).

The paper argues that garment-repair knowledge is dispersed, under-catalogued, and, at the living and invisible pole, actively vanishing. Rather than only call for an archive, this repository begins one. It is version 0.1: a first cartography that is openly incomplete and built to be extended with practitioners and curators.

## Contents

- `data/repair-traditions-atlas.csv` : the Repair Traditions Atlas, ~28 traditions scored against the seven-dimension repair-record schema.
- `data/atlas-codebook.md` : the codebook for the Atlas dimension values.
- `schema/repair-record.md` : the Repair Record, a data format for archiving a single act of mending (human-readable specification).
- `schema/repair-record.schema.json` : the same schema, machine-readable (JSON Schema draft-07).
- `records/rafoogari-najibabad.md` : the first deposited record, a living-practice and oral-history record of invisible reweaving.

## Standards

The Repair Record is an application profile of existing standards rather than a new silo: CIDOC-CRM and its CRMsci extension (which model alteration and intervention as events), W3C PROV (provenance of the record), and Europeana EDM-FP (fashion interoperability).

## Ethics and consent

Counter-archiving is legitimate only when coupled to the material conditions of the craft. Records that document living, named makers are deposited with consent and attribution, and with a commitment to benefit-sharing from any downstream use, including AI. Where a maker's full testimony is not yet cleared for open release, this repository holds a summary record and withholds the full transcript pending the maker's agreement on scope and benefit-sharing. The audiovisual interview behind the first record is shared as an unlisted video (linkable from the record, not broadcast or searchable) rather than as an open transcript (see `records/rafoogari-najibabad.md`).

## Licence

Data and documentation are released under CC BY 4.0 (SPDX: CC-BY-4.0), except where a specific record states otherwise for ethical reasons. See `LICENSE`.

## How to contribute

Repair traditions and individual repair records are welcome. Add a row to the Atlas (with sources), or a record under `records/` using the Repair Record schema, and open a pull request. The coding is first-pass and is to be validated with practitioners and curators.

## Citation

See `CITATION.cff`. Please cite this repository alongside the paper.

## Status

v0.1 (seed). Openly incomplete. Regional coverage is not comprehensive; the invisible-reweaving pole is prioritised because loss is imminent there.
