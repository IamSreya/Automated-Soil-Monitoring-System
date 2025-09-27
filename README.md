# 🌱 Automated Soil Monitoring System

A simple **Smart Soil Monitoring System** built using Arduino UNO, Soil Moisture Sensor, I2C LCD Display, and a Buzzer.  
This project measures soil moisture levels and **automatically alerts** when the soil is too dry, making it useful for **smart irrigation and agriculture automation**.

---

## 📌 Features
- Real-time soil moisture monitoring  
- Moisture percentage displayed on an **I2C 16x2 LCD**  
- **Buzzer alert** when soil is dry (< 30%)  
- Serial monitor output for debugging  
- Compact and low-cost design  

---

## 🛠 Tools & Components Used
- **Arduino UNO** (Microcontroller)  
- **Soil Moisture Sensor V2.0** (Analog output)  
- **I2C LCD Display (16x2)**  
- **Active Buzzer**  
- **Breadboard & Jumper Wires**  
- **USB Cable for Arduino**  
- **Arduino IDE** (for coding & uploading)  

---

## 🔌 Circuit Connections

### Soil Moisture Sensor → Arduino UNO
- **VCC → 5V**  
- **GND → GND**  
- **AOUT → A0**  

### I2C LCD → Arduino UNO
- **VCC → 5V**  
- **GND → GND**  
- **SDA → A4**  
- **SCL → A5**  

### Buzzer → Arduino UNO
- **+ → D8**  
- **- → GND**  

---


## ⚙️ How It Works
1. The soil moisture sensor detects the water content in the soil.  
2. The Arduino reads the analog values and converts them into a **percentage**.  
3. The LCD displays real-time soil moisture data.  
4. If the soil moisture drops below the threshold (30%), the **buzzer is activated automatically**.  


---

## 📖 Applications
- Smart Irrigation Systems  
- Greenhouse Monitoring  
- Precision Agriculture  
- Home Gardening Automation  
