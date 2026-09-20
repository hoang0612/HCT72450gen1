Sending special thanks to : https://easyeda.com/<img width="225" height="225" alt="tải xuống" src="https://github.com/user-attachments/assets/2960b80e-4f67-4169-8fc9-1685f5257ac9" />

# HCT72450gen1
 The new openesc-18mosfet project page is cleaner; you can view the old page here https://github.com/hoang0612/openESC-18MOSFET
# openESC-18MOSFET

An open-source 18-MOSFET EV controller developed by a 14-year-old hardware developer.

# ⚡ HCT72450 Gen 1 — High-Power Open-Source EV Controller

Special thanks to **EasyEDA** for supporting the early development of this project.

A high-performance, intelligent, open-source 3-phase BLDC/FOC motor controller designed for electric vehicles. This project combines automotive-grade power routing with advanced STM32 control, and is designed completely from scratch under extreme budget constraints using salvaged components.

---

## 🚀 Key Hardware Specifications

* **18-MOSFET Power Stage** — 3 parallel MOSFETs per half-bridge for high current capability.
* **60–72V Battery System** — Optimized for high-power EV applications.
* **Heavy Busbar Architecture** — Exposed 2oz copper layers designed to be reinforced with external copper busbars.
* **Shielded Gate Routing** — All gate-drive traces are routed inside the inner signal layer between solid GND planes for improved EMI immunity.
* **4-Layer PCB** — Dedicated power, ground, and signal routing architecture.
* **STM32F405RGT6** — 168 MHz ARM Cortex-M4 with hardware floating-point support.

---

## 🛠️ Firmware Features (In Development)

* Regenerative braking
* Hardware overcurrent protection (TIMx_BKIN)
* Bluetooth telemetry
* Temperature monitoring
* LoRa emergency overheating/fire alerts

---

## 📐 PCB Stackup

| Layer   | Function                |
| ------- | ----------------------- |
| Top     | 2oz Power & Busbar      |
| Inner 1 | Ground Plane            |
| Inner 2 | Shielded Signal Routing |
| Bottom  | 2oz Power Return        |

---

## 🧑‍💻 About

I'm a 14-year-old self-taught hardware and embedded firmware developer. This project is built almost entirely from recycled electronic components and designed as a long-term open-source learning platform for high-current EV control systems.

---

## 🤝 Sponsorship

This is a non-profit educational project. Hardware sponsorships and testing equipment are greatly appreciated to help manufacture and validate the first HCT72450 Gen 1 prototype.

---

# License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

You are free to use, study, modify, and redistribute this project under the terms of GPL-3.0. Any distributed modified versions must also remain open source under the same license.
You can see a few lines I didn't connect because those are the lines I use to get to the busbar.<img width="1366" height="768" alt="Screenshot (1005)" src="https://github.com/user-attachments/assets/77b832ac-373f-4e72-9785-1160e9c539b0" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3f499345-f1ca-4e2b-ac13-a3b2faf9248f" />
This final version will have some major changes, such as changing the shunt to three unidirectional shunts and a few other things. 
<img width="225" height="225" alt="tải xuống" src="https://github.com/user-attachments/assets/af58261a-85f3-4a89-b0cf-8930f57308f1" />
 special thank https://easyeda.com/
