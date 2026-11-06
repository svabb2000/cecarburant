# CeCarburant — date deschise

**[cecarburant.ro](https://cecarburant.ro)** — prețuri la carburanți în România, reconciliate la nivel de stație.

Generat la: 2026-11-06T12:16:53+00:00

Licență: **CC BY 4.0** — atribuire către CeCarburant.
Poți copia, modifica și redistribui liber datele, inclusiv comercial, cu condiția să păstrezi atribuirea și să menționezi modificările.

Datele sunt publicate doar în acest repository și în oglinda GitLab; nu sunt găzduite pe serverul cecarburant.ro.

## Repository

- Sursa principală: https://github.com/svabb2000/cecarburant
- Oglindă: https://gitlab.com/svabb2000/cecarburant

## Fișiere

- `stations_latest.csv` — 7546 rânduri stație/carburant, cu coordonate și ultimele prețuri consolidate.
- `national_current.csv` — 6 rânduri de agregate naționale.
- `national_history.csv` — 1116 rânduri de agregate naționale zilnice.
- `metadata.json` — metadate și schemă, în format citibil de mașină.
- `SHA256SUMS` — sume de control pentru verificarea fișierelor.

## Atribuire terță

`national_history.csv` este derivat din **PretCarburant.ro Open Data — Daily National Aggregates** de Stoian Andrei-Șerban /
PretCarburant.ro, licențiat **CC BY 4.0**, DOI
[10.5281/zenodo.19560194](https://doi.org/10.5281/zenodo.19560194), sursă
https://github.com/An3treiu/pretcarburant-data. Nu reprezintă date la nivel de stație și nu implică aprobarea autorului.

## Limitări

Prețurile sunt observații din surse publice și pot fi mai vechi decât prețul de la pompă.
Verifică `source_updated_at` și `observed_at` înainte de a lua decizii.