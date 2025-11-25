# STM32 PCB — KiCAD 9.0

**Compact 2-layer STM32-based PCB**

This repository contains the KiCAD 9.0 project files, documentation and assets for a compact 2-layer PCB built around an STM32 microcontroller. The board is designed for manufacturability on standard FR4 (1.6 mm) and targets hobbyist / low-volume production.

**Resource**

[KiCad 6 STM32 PCB Design Full Tutorial - Phil's Lab](https://www.youtube.com/watch?v=aVUqaB0IMh4&pp=ygULS0lDQUQgU3RtMzI%3D)

---

## Design specifications

* **Design software:** KiCAD 9.0
* **Microcontroller (MCU):** STM32 (schematic & part references in BOM)
* **Layers:** 2 (Top / Bottom)
* **Board dimensions:** **41 mm × 28.8 mm**
* **Substrate:** FR4, **1.6 mm** thickness
* **Files included:** KiCAD project files, schematic, PCB layout, Gerber export instructions, BOM
* **Protocols supported:** UART, I2C, SWD

---

## Repository layout (recommended)

```
/ (repo root)
├─ README.md
├─ STM32.kicad_pcb
├─ STM32.kicad_sch
├─ STM32.kicad_pro
├─ STM32.kicad_prl              
├─ /Manufacturing/            # Generated Gerber + drill files (ready for fab) in zip, BOM in CSV
├─ /images/                   # Schematic + top/bottom/layers view images
│   ├─ schematic.png
│   ├─ top_view.png
│   ├─ bottom_view.png
│   └─ layers_view.png
```

---

## Images

```markdown
![Schematic](images/schematic.png)
![Top View](images/top_view.png)
![Bottom View](images/bottom_view.png)
![Layers View](images/layers_view.png)
```

---

## BOM

All component details (reference designators, values, footprints, suppliers, and optional pricing) are in the attached BOM file. Download it here:

**[Download BOM](/Manufacturing/STM32_BOM.csv)**

---


