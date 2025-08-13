# Li-ion Battery Charging Circuit

This project is a **Li-ion battery charging circuit** designed for safe and reliable charging of single-cell lithium-ion batteries.  
The circuit provides **constant current / constant voltage (CC/CV)** charging, protecting the battery from overcharging and ensuring long battery life.

## 🔋 Features
- Safe charging for single-cell Li-ion batteries (3.7V nominal)
- Overcharge protection
- Automatic charge termination
- Constant current / constant voltage control


## 🛠 Components Used
- Li-ion battery charging IC (e.g., TP4056 or equivalent)
- Micro-USB or Type-C input connector
- Current limiting resistor
- Status indicator LEDs (Charging / Fully Charged)
- Protection MOSFETs (optional)

## ⚡ How It Works
1. The input voltage (typically 5V) is supplied via USB or external power source.
2. The charging IC regulates current and voltage to safely charge the battery.
3. LEDs indicate the charging status (blue = charging, green = charged).
4. The circuit automatically stops charging when the battery is full.
---
