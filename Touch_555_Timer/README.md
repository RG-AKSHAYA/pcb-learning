# Touch-Activated 555 Timer — Squeaky STEM Toy

An NE555-based monostable circuit that drives a piezo buzzer when a touch
input is triggered. Fully designed in KiCad from schematic to PCB layout.

---

## Circuit Details

- **IC:** NE555 Timer (monostable configuration)
- **Trigger:** Touch-sensitive input pad
- **Output:** Piezo buzzer activation
- **Power Supply:** Battery (portable, low-voltage)
- **Construction:** Through-hole components

---

## Design Process

### 1. Schematic Capture
Full circuit schematic designed in KiCad EESchema.

![Schematic](schematic.png)

### 2. Footprint Assignment
Through-hole footprints assigned to all components, linking schematic
symbols to physical PCB dimensions for accurate layout generation.

![Footprint Assignment](footprint.png)

### 3. Net Class Configuration
Separate net classes configured for power, signal, and output traces
to ensure clean routing and organized PCB structure.

![Net Class Setup](netclass.png)

### 4. PCB Layout
Compact routed PCB with organized component placement and clean trace routing.

![PCB Layout](pcb_wiring.png)

### 5. 3D Verification
3D preview generated to verify component placement, orientation, and
overall board appearance before fabrication.

![3D PCB View](pcb.png)

---

## Tools
- KiCad 8 (EESchema, PCB Editor, 3D Viewer)

---

## Files in This Folder
| File | Description |
|---|---|
| `schematic.png` | Circuit schematic |
| `footprint.png` | Footprint assignments |
| `netclass.png` | Net class configuration |
| `pcb_wiring.png` | Routed PCB layout |
| `pcb.png` | 3D PCB preview |
