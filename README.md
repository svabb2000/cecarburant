# CeCarburant Open Data

**[cecarburant.ro](https://cecarburant.ro)** — prețuri la carburanți în România, reconciliate la nivel de stație.

Generated at: 2026-11-06T11:39:34+00:00

License: **CC BY 4.0** — attribution to CeCarburant.
Modify the data freely, but keep this attribution and indicate changes.

## Repository

- Primary: https://github.com/svabb2000/cecarburant
- Mirror: https://gitlab.com/svabb2000/cecarburant

## Files

- `stations_latest.csv` — 7546 station/fuel rows with coordinates and latest consolidated prices.
- `national_current.csv` — 6 national aggregate rows.
- `national_history.csv` — 1116 daily national aggregate rows.
- `metadata.json` — machine-readable metadata and schema.
- `SHA256SUMS` — checksums.

## Third-party attribution

`national_history.csv` is derived from **PretCarburant.ro Open Data — Daily National Aggregates** by Stoian Andrei-Șerban /
PretCarburant.ro, licensed **CC BY 4.0**, DOI
[10.5281/zenodo.19560194](https://doi.org/10.5281/zenodo.19560194), source
https://github.com/An3treiu/pretcarburant-data. It is not station-level data and does not imply endorsement.

## Caveats

Prices are observations from public sources; they may lag behind the pump.
Check `source_updated_at` and `observed_at` before making decisions.