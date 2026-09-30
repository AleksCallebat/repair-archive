# The Repair Record

A data format for archiving a single act of mending, so that a mend becomes a comparable, searchable unit rather than an incidental property of a catalogued garment.

It operates at two levels: the *tradition* level (the seven-dimension schema and the Atlas built from it) and the *instance* level (this Repair Record, for one repair).

It is built as an application profile of existing standards rather than a new silo: CIDOC-CRM and its CRMsci extension (alteration and intervention as events), W3C PROV (provenance of the record itself), and Europeana EDM-FP (fashion interoperability).

## Fields

| Ref | Field group | What it records |
|-----|-------------|-----------------|
| A | Object and context | ID; garment/textile type; fibre and construction; provenance; cultural origin; link to Atlas tradition |
| B | Damage (before) | Damage type, location, extent and measurements, cause; before-image(s); date |
| C | Intervention (technique) | Technique (controlled vocabulary and intent mode); tools; materials and yarns; time-coded step sequence; skill register; time taken; maker and attribution |
| D | Result (after) | After-image(s); detectability score (0 to 5); durability; reversibility |
| E | Physical specimen | Technique swatch and/or removed material sample |
| F | Rights and governance | Maker consent; attribution; cultural-IP and licence; community governance |
| G | Record provenance | Recorder; date; capture method (per PROV) |

## Capture modes

No single medium suffices, least of all for invisible work. A record draws on complementary, non-exhaustive modes:

1. Written technique documentation (steps, pattern, materials).
2. Audiovisual recording of the actions (process video, and where warranted motion capture).
3. A physical technique sample (a worked swatch; the living descendant of the darning sampler).
4. Before, during and after imaging, with the damage documented first so the invisible result is legible against it.

For invisible reweaving all four are needed; a bold visible darn may need only an after-image and a note.

## Standards mapping (summary)

- B (damage) maps to a CRMsci alteration / observation event.
- C (intervention) maps to a CIDOC-CRM activity (E7) bearing actors (E39), tools, and materials (E57).
- D (result) maps to the resulting condition state / outcome.
- G (record provenance) maps to W3C PROV (agent, activity, entity).
