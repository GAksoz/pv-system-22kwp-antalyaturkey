# ☀️ 22 kWp Grid-Connected PV System Design (PVsyst Simulation)

This repository presents the simulation and performance analysis of a **22 kWp rooftop photovoltaic (PV) system** designed using **PVsyst v7.4.8**. The project is based in **Kömürcüler, Antalya, Turkey**, using **550 W Trina Solar modules** and a **Huawei SUN2000 inverter**.

---

## 🧾 System Overview

| Parameter                  | Value                          |
|----------------------------|--------------------------------|
| **Location**               | Kömürcüler, Antalya, Turkey   |
| **PV Module Power**        | 550 W                         |
| **Number of Modules**      | 40                            |
| **Total DC Power**         | 22.0 kWp                      |
| **Inverter Model**         | SUN2000-20KTL-M2              |
| **Inverter Manufacturer**  | Generic                       |
| **Inverter Power (AC)**    | 20.0 kW                       |
| **Number of Inverters**    | 1                             |
| **DC/AC Ratio**            | 1.10                          |
| **Array Configuration**    | 4 strings × 10 modules        |
| **PV Tilt / Azimuth**      | 7° / 0° (south facing)        |
| **PV Surface Area**        | 105 m²                        |
| **Albedo**                 | 0.20                          |
| **Altitude**               | 303 m                         |
| **Weather Data**           | Meteonorm 8.1 (2003-2013)     |

---

## 📊 Performance Summary

| Metric                          | Value               |
|---------------------------------|---------------------|
| **System Size (DC)**            | 22.0 kWp            |
| **Specific Production**         | 1,447 kWh/kWp/year  |
| **Total Energy Output**         | 31,826 kWh/year     |
| **Performance Ratio (PR)**      | 84.97 %             |
| **Thermal Loss Coefficient**    | 20 W/m²K            |
| **Module Quality Loss**         | -0.4 %              |
| **Module Mismatch Loss**        | 2.0 %               |
| **DC Wiring Losses**            | 0.95 %              |
| **Inverter Efficiency Losses**  | 2.63 %              |

---

## ⚡ Loss Diagram Summary

- Global horizontal irradiation: 1,626 kWh/m² (+4.7% plane of array)
- IAM losses: -2.86 %
- PV conversion nominal energy (STC): 36,391 kWh
- Irradiance level losses: -0.73 %
- Temperature losses: -7.02 %
- Module quality: +0.38 %
- Mismatch (module & string): -2.05 %
- DC ohmic wiring losses: -0.95 %
- Inverter losses (operation): -2.63 %
- Night consumption: -0.08 %
- **Energy injected to grid: 31,826 kWh/year**

---

## 📁 Included Files

- 📄 `20kW_Project_Report.pdf` – Full PVsyst simulation report
- 🖼️ `pv_layout.dwg` – PV module layout (string diagram or 3D view)
- 📊 `monthly_output.xlsx` – Monthly energy production table and charts
- 📈 `system_specs.xlsx` – Design and performance summary table

---

## 🧠 Notes

- System modeled as **unshaded (open rooftop)**.
- Inverter loaded at 110% DC/AC ratio within design best practice.
- Weather data from **Meteonorm TMY (2003-2013)**.
- Simulation performed under **PVsyst evaluation mode** for academic and training use.

---

## 📌 Author

Designed and simulated by **Gani Aksöz**, Electrical & Electronics Engineering Student  
Date: July 2025  
Tool: **PVsyst v7.4.8, AutoCAD 2025**
