# AC to DC Converter PCB (Bridge Rectifier Power Supply)

A beginner-friendly PCB design of a **linear AC to DC power supply** created using KiCad.
This project converts low-voltage AC from a step-down transformer into filtered DC output using a full bridge rectifier and smoothing capacitor.

> ⚠️ This circuit is designed for transformer output (9–15VAC).
> **DO NOT connect directly to 230V mains.**

---

## 📌 Features

* Full bridge rectifier using 1N4007 diodes
* Ripple filtering using electrolytic capacitor
* Power indication LED
* Screw terminal input/output connectors
* Single layer PCB (easy to manufacture)
* 3D modeled board

---

## 🧠 Working Principle

1. AC voltage from a step-down transformer enters through input terminal
2. Four diodes form a bridge rectifier converting AC → pulsating DC
3. Electrolytic capacitor smooths ripple and produces DC
4. LED indicates output presence
5. DC available at output terminal

[
V_{DC} ≈ 1.414 × V_{AC(rms)} − 2V_d
]

Example:
12VAC → ~15–17V DC (no load)

---

## 🗂️ Files Included

| File       | Description         |
| ---------- | ------------------- |
| Schematic  | Circuit diagram     |
| PCB Layout | Routed PCB          |
| 3D Model   | Board preview       |
| Gerbers    | Manufacturing files |

---

## 🔧 Components Used

| Component | Value                         |
| --------- | ----------------------------- |
| D1–D4     | 1N4007 Diodes                 |
| C1        | 1000µF Electrolytic Capacitor |
| R1        | 10kΩ                          |
| R2        | 2.2kΩ                         |
| D5        | LED                           |
| J1, J2    | Screw Terminals               |

---

## 📤 Output Voltage

| AC Input | Approx DC Output |
| -------- | ---------------- |
| 9VAC     | ~12V             |
| 12VAC    | ~16V             |
| 15VAC    | ~20V             |

*(varies with load)*

---

## ⚠️ Safety

* Use **only transformer isolated AC**
* Do not connect mains supply
* Not a regulated power supply
* Output voltage changes with load

---

## 🛠️ Designed With

* KiCad (Schematic & PCB)
* KiCad 3D Viewer

---

## 🎯 Learning Objectives

This project helped me learn:

* Bridge rectifier design
* Capacitor filtering
* PCB routing for power circuits
* Footprints & 3D modeling
* Basic power electronics layout rules

---

## 🚀 Future Improvements

* Add voltage regulator (7805 / 7812)
* Add fuse protection
* Add reverse polarity protection
* Add heatsink support

---

## 👨‍💻 Author

**Mayank Pandey**, 
Electronics Engineering Student, 
HBTU KANPUR

---

⭐ If you found this useful, feel free to star the repository!
