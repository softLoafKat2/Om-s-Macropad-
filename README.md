# Om's Macropad

**Author:** Om  
**Status:** Prototype — PCB & Gerbers ready (v1.0)

## Project summary
A compact macropad based on ESP32-WROOM with 4 mechanical buttons and a rotary encoder (push), plus a small I²C OLED. Designed for custom macros and volume control.

Features:
- ESP32-WROOM module (Wi-Fi + BLE)
- 4 mechanical push buttons
- 1 rotary encoder with push
- Small I²C OLED screen
- Single-layer keepout for antenna, ground pour present

## Files in this repo
- `Om-s-macropad_v1.0_gerber.zip` — Gerber files for board fabrication (v1.0)
- `bom.csv` — Bill of materials (basic)
- `pick_and_place.csv` — Pick-and-place coordinates (if needed)
- `schematic.pdf` — Schematic export
- `pcb-top.png` — Top view image of the board
- `project.easyeda` — (optional) EasyEDA project export

## BOM (short)
- ESP32-WROOM (module) — QTY 1
- Tactile switch (SKRAAME010) — QTY 4
- Rotary encoder (EC110104S2A...) — QTY 1
- OLED (I2C 0.96") — QTY 1
- Misc: resistors, caps (if used), headers, screws (optional)

## Notes for fab & assembly
- Keep antenna keep-out as provided in the PCB (do not fill with copper)
- Solder mask: default (green/black)
- Board thickness: 1.6mm recommended
- Surface finish: ENIG or HASL (factory choice)
- For small runs use JLCPCB / PCBWay

## License
This project is released under the MIT License. See `LICENSE` for details.

---

If you need me to create the BOM table, populate `README` with images, or upload the Gerber zip to the release, say which file(s) you need help with and I’ll prepare the text/images you can paste or upload directly.
