# PCBee

A small CNC machine for milling PCBs
It can also handle engraving and light milling tasks. 

*Batteries not included.* ⚡

---
## ⚠️ Warning

While the machine design is pretty much complete, the **BOM is not fully finalized** and i still have to add some stuff like a proper enclosure for electronics.
Screws, nuts, and other fasteners are not yet listed.  

You can download the provided **CAD files** and check the assembly to get an idea of the exact fasteners required.  

## 📐 Machine Specifications

### Total Machine Size
- **Y:** 290 mm  
- **X:** 285 mm  
- **Z:** 250 mm  

### Work Area
- **X:** 120 mm  
- **Y:** 120 mm  
- **Z:** 25 mm *(Z travel — not including endmill)*  

---

## 🧰 Bill of Materials (BOM)

### Printed Parts
- Can also be **laser-cut, milled, or even cut by hand**. DXF files are provided.  

---

### Extrusion
- 6 × 2020 120 mm *(or 3 × 2040, or 2 × 2060)* → **Bed**  
- 2 × 2040 220 mm → **Chassis**  
- 2 × 2020 200 mm → **X-axis**  

---

### Smooth Rods
- 2 × Ø10 mm × 220 mm → **X-axis**  
- 2 × Ø10 mm × 237 mm → **Y-axis**  
- 2 × Ø8 mm × 100 mm → **Z-axis**  

---

### Bearings
- 8 × LM10UU → **X and Y axis**  
- 4 × LM8UU → **Z axis**  
- 2 × 908 Ball Bearings → **X/Y leadscrew support** *(optional, but looks cool)*  

---

### Other
- 3 × Shaft Couplers *(avoid the "spring" type since those can cause backslash)*  
- 2 × TR8 Leadscrews 210 mm + Anti-Backlash Nuts → **X and Y axis**  
- 1 × TR8 Leadscrew 100 mm + Normal Nut → **Z axis**  

---

## ⚡ Electronics

- 1 × Arduino UNO  
- 1 × CNC Shield  
- 1 × 40×40 12V Fan  
- 1 × 775 Motor + ER11 Collet *(avoid the "drill chuck" type)*  
- 2 × Relay Boards *(optional, used to toggle spindle/aspiration via gcode)*  
- 3 × Stepper Drivers *(A4988 recommended for low cost)*  
- 3 × NEMA 17 Stepper Motors  
- 1 × 12V "Super Slim LED Strip" PSU *(~300W is plenty)*  

---

## 🚧 Notes

- Design is intended for **PCB milling**, but it’s versatile enough for **engraving** and light material removal.  
- Many components can be swapped with equivalents depending on what you have on hand.  

---

## 📜 License

[MIT License](LICENSE)  
