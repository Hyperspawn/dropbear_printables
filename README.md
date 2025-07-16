# Dropbear Printable Parts

This repo contains all 3D-printable components for assembling **Dropbear**. It includes subassembly-wise `.3mf` print plates, exploded view images, and guidelines to help you print, prepare, and assemble the robot.

---
<img width="300" height="300" alt="Right Leg 3D Printable" src="https://github.com/user-attachments/assets/cc5796e8-4c5e-4b9e-813f-81fa9d825714" />
<img width="300" height="300" alt="Right Arm 3D Printable" src="https://github.com/user-attachments/assets/0aaef4f2-cf4a-44a9-bb9d-e8f28149bf2c" />
<img width="300" height="300" alt="Pelvis 3D Printable" src="https://github.com/user-attachments/assets/21583474-02d9-4a7d-b3f3-aa0b01e1f755" />
<img width="300" height="300" alt="Head 3D Printable" src="https://github.com/user-attachments/assets/131213f5-afcb-4bce-aa4b-1fb347a74cc5" />
<img width="300" height="300" alt="Left Leg 3D Printable" src="https://github.com/user-attachments/assets/1f07dd51-e995-430e-b845-2d66654f2edf" />
<img width="300" height="300" alt="Left Arm 3D Printable" src="https://github.com/user-attachments/assets/cd8b818c-7adb-4a46-9404-cbe0aa7767bd" />

## 📁 Repository Structure

```
dropbear_printables/
│   ├── head/
│       └── plates/
│       └── STLs/
│   ├── torso/
│   ├── left_arm/
│   ├── right_arm/
│   ├── left_leg/
│   ├── right_leg/
│   └── pelvis/
├── print_settings.md/
└── README.md
```

## 🚀 Getting Started

```bash
git clone https://github.com/Hyperspawn/dropbear_printables.git
```

Open `.3mf` files in PrusaSlicer, Bambu Studio, or Cura for a pre-arranged plate of parts.

<img width="495" height="329" alt="image" src="https://github.com/user-attachments/assets/a4ef31f3-188d-4fd1-8e9d-c6adaf9b0399" />


## 🖨️ Print Settings (Recommended)

| Setting         | Value                     |
|----------------|---------------------------|
| Layer Height    | 0.2 mm                    |
| Infill          | 40–60%                    |
| Supports        | Where indicated           |
| Walls/Perimeters| 3                         |
| Material        | PETG / ABS (preferred)    |

- Use **PLA** only for prototypes.
- **TPU** may be needed for specific damping/flexible parts.



## 🧱 Subassemblies

Each subassembly folder includes:
- `.3mf` print plate file
- Individual `.stl` part files




## 🖼️ Visuals

All rendered and exploded views are in the `renders/` directory to help during assembly. You may reference these when printing or aligning orientation.



## ✅ Tips

- Double-check orientations for parts with overhangs.
- For strength-critical parts (like leg brackets), prefer **CF-PETG** or **Nylon**.
- Mirror right-arm or right-leg parts as needed unless a separate folder exists.



## 📜 License

Open-source under MIT. Commercial use permitted with attribution.

---

Make. Print. Assemble. Hack. 🛠️

