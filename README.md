# 3.3V-5V-Voltage-regulator
12V & 5V/3.3V Dual Power Supply Module

A custom printed circuit board designed in KiCad to regulate high-voltage inputs down to clean 5V and 3.3V rails.

📝 Project Overview

This project provides a stable power foundation for microcontrollers (like the ESP32) while allowing them to control 12V peripherals. It features proper ground plane isolation, thermal reliefs, and optimized current return paths to minimize switching noise.

🖼️ Board Views

3D Render

(Upload your 3D view PNG to GitHub, then change the filename below to match)


Schematic

(Upload your Schematic PNG to GitHub, then change the filename below to match)


PCB Layout (Top & Bottom)

(Upload your PCB layout PNG to GitHub, then change the filename below to match)


🗂️ Files Included

*.kicad_pro, *.kicad_sch, *.kicad_pcb: The raw KiCad 10 project files.

/PDFs: Downloadable PDF versions of the schematic and copper layers.

/Gerbers: (Optional) Production files ready to be sent to a manufacturer like JLCPCB.

⚙️ Key Specifications

Input Voltage: 12V DC (Barrel Jack)

Output Voltages: 12V, 5V, 3.3V

Layers: 2-Layer (F.Cu, B.Cu with solid GND plane)

Design Software: KiCad 10

🛠️ How to Use

Clone this repository.

Open the .kicad_pro file in KiCad 10 or newer.

To manufacture, zip the /Gerbers folder and upload it to your preferred fab house.
