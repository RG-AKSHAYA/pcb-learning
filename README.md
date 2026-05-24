# PCB Design Projects — KiCad

Hardware designs including schematics, PCB layouts, and Gerber-ready files
built using KiCad. Focused on embedded and analog circuits.

---

## Touch-Activated 555 Timer — Squeaky STEM Toy

An NE555-based astable/monostable circuit that drives a buzzer on touch input.
Designed as a complete PCB-ready project: from schematic capture to 3D-verified layout.

### Circuit Overview
- **IC:** NE555 Timer (monostable configuration)
- **Input:** Touch-sensitive trigger
- **Output:** Piezo buzzer
- **Power:** Battery-operated
- **Components:** NE555, resistors, capacitors, buzzer

### What Was Designed
| Stage | Details |
|---|---|
| Schematic | Full schematic capture in KiCad EESchema |
| Footprint Assignment | Through-hole footprints assigned to all components |
| Net Classes | Separate classes for power, signal, and output traces |
| PCB Layout | Compact routed layout with organized component placement |
| 3D Verification | KiCad 3D viewer used to verify placement and orientation |

### Design Files
- `schematic.png` — Circuit schematic
- `footprint.png` — Footprint assignments
- `netclass.png` — Net class configuration
- `pcb_wiring.png` — Routed PCB layout
- `pcb.png` — 3D PCB preview

### Tools Used
- KiCad (Schematic + PCB layout + 3D viewer)

---

