# 🛫 Repülőjegy Foglalási Rendszer

Ez a Python projekt egy egyszerű szöveges felületen működő repülőjegy-foglalási rendszert valósít meg.

## 📁 Fájlok

- `repulojegy.py` – a főprogram a rendszer működéséhez
- `adatok.txt` – tartalmazza a készítő nevét, szakját és Neptun-kódját (kötelező a beadáshoz)

## 🧠 Funkcionalitás

- Jegy foglalása megadott járatra
- Foglalás lemondása járatszám alapján
- Jelenlegi foglalások listázása
- Összes járat listázása
- Adatellenőrzés (csak létező járatra lehet foglalni, csak meglévő foglalás törölhető)

## 📦 Előre betöltött adatok

A program indulásakor automatikusan betöltésre kerül:

- **1 légitársaság**: Magyar Air
- **3 járat**:
  - Belföldi: Debrecen, Pécs
  - Nemzetközi: Berlin
- **3 foglalás** ezekre a járatokra

## ▶️ Használat

A futtatáshoz:

```bash
python repulojegy.py
