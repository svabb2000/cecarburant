# CeCarburant — date deschise

**[cecarburant.ro](https://cecarburant.ro)** — prețuri la carburanți în România, reconciliate la nivel de stație.

Generat la: 2026-11-08T17:16:16+02:00

Licență: **CC BY 4.0** — atribuire către CeCarburant.
Poți copia, modifica și redistribui liber datele, inclusiv comercial, cu condiția să păstrezi atribuirea și să menționezi modificările.

Datele sunt publicate doar în acest repository și în oglinda GitLab; nu sunt găzduite pe serverul cecarburant.ro.

## Repository

- Sursa principală: https://github.com/svabb2000/cecarburant
- Oglindă: https://gitlab.com/svabb2000/cecarburant

## Fișiere

- `stations_latest.csv` — 4957 rânduri stație/carburant, cu coordonate și ultimele prețuri consolidate.
- `national_current.csv` — 6 rânduri de agregate naționale.
- `national_history.csv` — 32 rânduri de agregate naționale calculate din observațiile noastre.
- `metadata.json` — metadate și schemă, în format citibil de mașină.
- `SHA256SUMS` — sume de control pentru verificarea fișierelor.

## Limitări

Prețurile sunt observații din surse publice și pot fi mai vechi decât prețul de la pompă.
Verifică `source_updated_at` și `observed_at` înainte de a lua decizii.