# M626 Trickle Charger · Unsorted

Ward-Beck Systems M626, 1971|4. Wiki page: [M626 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M626.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 5 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 2 |

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

Not on Google Drive yet: `1971 - 626-02-001 - TRICKLE CHARGER SCHEMATIC - DRN TY - ISS 1.png`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `1971 - 626-02-002 - FRAME CONNECTOR WIRING - DRN TY - ISS 1.png`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-7 | AC LINE | power | AC | medium |
| P1-16 | AC LINE | power | AC | medium |
| P2-1 | +B1 MEASURE | control_out | +B1 MEASURE + | medium |
| P2-5 | +B1 | strap |  | medium |
| P2-6 | +B1 OUT | out | +B1 OUT + | medium |
| P2-12 | CHASSIS GROUND | ground |  | medium |
| P2-14 | COMMON | ground |  | medium |
| P2-15 | COMMON | ground |  | medium |
| P2-16 | COMMON | ground |  | medium |

**Straps:** 5-6: P2-5 P2-6 · 14-15-16: P2-14 P2-15 P2-16

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1971 - 626-02-001 - TRICKLE CHARGER SCHEMATIC - DRN TY - ISS 1.kicad_sch](KICAD/1971%20-%20626-02-001%20-%20TRICKLE%20CHARGER%20SCHEMATIC%20-%20DRN%20TY%20-%20ISS%201.kicad_sch)
- [1971 - 626-02-002 - FRAME CONNECTOR WIRING - DRN TY - ISS 1.kicad_sch](KICAD/1971%20-%20626-02-002%20-%20FRAME%20CONNECTOR%20WIRING%20-%20DRN%20TY%20-%20ISS%201.kicad_sch)
- [M626.kicad_sym](KICAD/M626.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
