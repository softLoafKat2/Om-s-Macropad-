# Om's Macropad
A macropad with 4 programmable buttons that can help ya do tasks along with a dial to control volume.
A small ESP32-based macropad (4–6 buttons + rotary encoder) that connects to Android via BLE HID. This repo contains:

firmware/om_macropad.ino — Arduino BLE firmware (ready for ArduinoDroid)
hardware/schematic.png — schematic instructions & annotated mockup
hardware/pcb_mockup.png — silk/top view (80×40 mm)
case/om_macropad_top.stl and case/om_macropad_bottom.stl (or case_instructions.txt)
BOM.csv — bill of materials with suggested parts
LICENSE — MIT

# How to flash (tablet-only)
Install ArduinoDroid on your Android tablet.
Open firmware/om_macropad.ino, install ESP32 board support and the ESP32 BLE Keyboard library.
Connect your ESP32 using USB-OTG or a USB-serial adapter and upload.

# Quick notes
Uses GPIO pins: BTN1=32, BTN2=33, BTN3=25, BTN4=26, ENC_A=4, ENC_B=16, ENC_SW=17 (modify in firmware if needed).
