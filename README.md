# 🔋 Li-Ion Battery Charging Module with MCP73831

This project is a compact and reliable **single-cell Li-Ion/Li-Po battery charging board** using the **MCP73831T-2ACI/OT** linear charger IC. Designed for prototyping, IoT devices, and embedded systems requiring safe and simple battery charging from a 5V USB or adapter input.

---

## 📦 Features

- ✅ Input overvoltage and surge protection (TVS diode + fuse)
- ✅ Single-cell Li-Ion/Li-Po battery charging (4.2V, 500 mA)
- ✅ Charging status LED indicator (ON during charging, OFF when fully charged)
- ✅ Clean and simple 2-layer PCB design
- ✅ Output connector for system power
- ✅ Mounting holes and large battery cutout for easy integration

---

## ⚙️ Technical Specifications

| Parameter           | Value                   |
|--------------------|-------------------------|
| Charging IC        | MCP73831T-2ACI/OT       |
| Input Voltage      | 5V DC                   |
| Charging Current   | 500 mA (set via 2 kΩ resistor) |
| Battery Voltage    | 3.7V Nominal (4.2V max) |
| Capacitors         | 10µF & 4.7µF Ceramic    |
| Protections        | Fuse, TVS Diode         |

---

## 🧩 Schematic & PCB

The design is created using **KiCad** and includes:
- Complete schematic (.sch)
- PCB layout (.kicad_pcb)
- Gerber files for fabrication
- Bill of Materials (BOM)

---

## 🛡️ Battery Protection

> ⚠️ **Note**: This board does **not include battery protection** circuitry.  
Use **protected Li-Ion cells** or add an external **battery protection module** (e.g., DW01 + FS8205A) to ensure safe operation.

---

## 🖼️ Preview

### 📷 PCB Layout (Top View)
![image](https://github.com/user-attachments/assets/c467aa31-558a-443d-b8ec-402800788fcb)


---

## 📁 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute with attribution.

---

## 🤝 Contributions

Pull requests and suggestions are welcome!  
Feel free to open issues for improvements or bugs.

---

## 📧 Contact

Created by **Nishanth Kiruthivasan**  
📬 nishvask@gmail.com | kiruthivasan.n@northeastern.edu

🔗 [Portfolio]([url](https://nishanthkiruthivasan.carrd.co/))
