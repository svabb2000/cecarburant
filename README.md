# CeCarburant — date deschise

**[cecarburant.ro](https://cecarburant.ro)** — prețuri la carburanți în România, reconciliate la nivel de stație.

Generat la: 2026-11-09T20:42:14+02:00

Licență: **CC BY 4.0** — atribuire către CeCarburant.
Poți copia, modifica și redistribui liber datele, inclusiv comercial, cu condiția să păstrezi atribuirea și să menționezi modificările.

Datele sunt publicate doar în acest repository și în oglinda GitLab; nu sunt găzduite pe serverul cecarburant.ro.

## Repository

- Sursa principală: https://github.com/svabb2000/cecarburant
- Oglindă: https://gitlab.com/svabb2000/cecarburant

## Fișiere

- `stations_latest.csv` — 6970 rânduri stație/carburant, cu coordonate și ultimele prețuri consolidate.
- `national_current.csv` — 6 rânduri de agregate naționale.
- `national_history.csv` — 2863 rânduri de agregate naționale (săptămânale din 2008 și zilnice pentru perioada recentă).
- `metadata.json` — metadate și schemă, în format citibil de mașină.
- `SHA256SUMS` — sume de control pentru verificarea fișierelor.

## Atribuire terță

`national_history.csv` include prețuri naționale săptămânale derivate din
**European Commission — Weekly Oil Bulletin**, licență **© European Commission — reuse with attribution**, sursă
https://energy.ec.europa.eu/data-and-analysis/weekly-oil-bulletin_en. National weekly retail prices for Euro-super 95, automotive diesel and LPG, converted from EUR/1000 l to RON/l with the EUR/RON rate published in the same bulletin. Nu implică aprobarea Comisiei Europene.
Perioada recentă este completată cu snapshot-uri zilnice CeCarburant.

## Limitări

Prețurile sunt observații din surse publice și pot fi mai vechi decât prețul de la pompă.
Verifică `source_updated_at` și `observed_at` înainte de a lua decizii.