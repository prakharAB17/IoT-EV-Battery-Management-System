## 🔧 Hardware Model Preview

![Hardware Model](Hardware/hardware_model.jpeg)


# ⚡ IoT Based EV Battery Management System  
🔋 Real-Time Charge Monitoring & Fire Protection for Electric Vehicles

<div align="center">

![Arduino](https://img.shields.io/badge/Arduino-UNO-blue)
![IoT](https://img.shields.io/badge/Technology-IoT-green)
![EV](https://img.shields.io/badge/Application-Electric%20Vehicle-red)
![IEEE](https://img.shields.io/badge/Publication-IEEE%202024-orange)

</div>

---

## 📌 Project Overview

This project presents an **IoT-based Battery Management System (BMS)** for Electric Vehicles with **real-time charge monitoring and fire protection**.  
The system continuously monitors:

- 🔹 Battery Voltage  
- 🔹 Battery Current  
- 🔹 Battery Temperature  

If any parameter exceeds the safe operating limit:
✅ **Auto Cut-Off activates**  
✅ **Cooling Fan turns ON**  
✅ **Buzzer Alert is triggered**  
✅ **Real-time notification is sent to Mobile App via ESP8266**

---

## 🎯 Key Features

✅ Real-Time IoT Monitoring  
✅ Android Mobile App Integration  
✅ Over-Charging Protection  
✅ Thermal Runaway Prevention  
✅ Fire Protection System  
✅ Automatic Power Cut-Off  
✅ BLDC Motor Based EV Drive  
✅ LCD Display Monitoring  

---

## 🛠 Hardware Components Used

| Component | Description |
|----------|-------------|
| Arduino UNO | Main Controller |
| ESP8266 WiFi Module | IoT Communication |
| LM35 Temperature Sensor | Heat Monitoring |
| Voltage Sensor | Battery Voltage |
| Current Sensor | Battery Load |
| 5V Relay Module | Power Switching |
| Li-Ion Battery (3 Cell) | Energy Storage |
| BLDC Motor | Vehicle Drive |
| 16x2 LCD | Live Display |
| Buzzer & Cooling Fan | Safety Module |

---

## ⚙️ System Working Principle

1️⃣ Sensors collect Voltage, Current & Temperature  
2️⃣ Data is processed by **Arduino UNO**  
3️⃣ Data is sent to Mobile via **ESP8266 IoT Module**  
4️⃣ If:
- Temperature > 45°C  
- Voltage exceeds limit  
→ **Relays cut OFF Power Automatically**
→ **Fan & Buzzer turn ON**

---

## 🧠 Technologies Used

- Embedded Systems  
- Internet of Things (IoT)  
- Arduino Programming  
- EV Power Electronics  
- Battery Protection Algorithms  

