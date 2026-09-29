# ATmega32 Temperature Monitoring System (PCB Design)

A complete hardware design for an embedded temperature measurement and display system based on the **Microchip/Atmel ATmega32A** microcontroller, designed in **Altium Designer**.

---

## 📌 Project Overview
- **Microcontroller:** ATmega32A (TQFP / DIP package)
- **Sensor:** LM35 Precision Centigrade Temperature Sensor ($10\text{ mV}/^\circ\text{C}$)
- **Analog Front-End:** LM358 Operational Amplifier for signal conditioning & filtering
- **Display:** 16x2 Alphanumeric Character LCD
- **PCB Dimensions:** $88.65\text{ mm} \times 49.28\text{ mm}$
- **Layers:** 2-Layer Board (Top & Bottom routing with GND solid copper pours)

---

## 🛠️ Hardware Features
- Regulated $5\text{V}$ power supply circuit with decoupling capacitors.
- On-board contrast potentiometer for the LCD.
- Standard In-System Programming (ISP) header.
- Crystal oscillator circuitry ($16\text{ MHz}$) with load capacitors.
- Fully DRC-verified layout with zero unrouted nets.

---

## 📂 Repository Structure
- `/Design Files`: Altium Designer project, schematic, and PCB layouts (`.PrjPcb`, `.SchDoc`, `.PcbDoc`).
- `/Outputs`: Fabrication outputs including Gerber RS-274X, NC Drill files, and Bill of Materials (BOM).
