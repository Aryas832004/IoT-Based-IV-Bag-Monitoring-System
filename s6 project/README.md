# 💧 IoT-Based IV Bag Monitoring System

An innovative IoT solution designed to enhance patient safety and reduce the manual workload of medical staff by continuously monitoring IV fluid levels and sending real-time alerts.

---

## 📚 Project Overview

Intravenous (IV) therapy plays a crucial role in clinical care. However, manual monitoring of IV fluid levels is time-consuming and prone to human error. This project presents an **IoT-based IV Bag Monitoring System** using the **ESP8266 microcontroller**, **load cell**, and **Blynk platform** to automate IV fluid monitoring. Alerts are sent to a mobile app when fluid levels drop below a critical threshold.

This project was presented at the **International Conference on Advancement in Science, Engineering & Technology (ICASET)** and is expected to be published officially soon.

---

## 🧑‍🏫 Supervised By

**Ms. Swetha C**  
Assistant Professor  
Department of Electronics and Communication Engineering  
Ahalia School of Engineering and Technology

---

## 👥 Team Members

- Arya Sasikumar 
- Gowthami S  
- Mahitha M  
- Ajmal T A

---

## ⚙️ Key Features

- 📦 **Real-time Monitoring** – Load cell detects IV fluid weight continuously.
- 📲 **IoT Alerts** – Sends notifications via Blynk when fluid is low.
- 🖥 **LCD Display** – Shows current IV bag weight.
- 🔴 **LED Indicator** – Visual cue for nearby staff.
- 🌐 **Remote Access** – Enables off-site monitoring through Wi-Fi.

---

## 🔧 Hardware & Software

| Component             | Description                           |
|----------------------|---------------------------------------|
| ESP8266 NodeMCU      | Microcontroller with Wi-Fi            |
| Load Cell (10kg)     | Senses IV fluid weight                |
| HX711 Amplifier      | Amplifies and digitizes sensor data   |
| 16x2 LCD with I2C    | Displays IV weight locally            |
| LED                  | Indicates low fluid alert             |
| Power Supply (5V)    | External DC adapter or battery        |
| Arduino IDE          | Code development                      |
| Blynk App            | Remote monitoring via smartphone      |

---

## 🧠 Working Principle

1. **Initialization**: ESP8266 powers up and calibrates the load cell via HX711.  
2. **Weight Monitoring**: Real-time weight data is acquired and processed.  
3. **Display Output**: Weight is shown on the 16x2 LCD using I2C.  
4. **Threshold Detection**: If fluid drops below set limit:
   - Red LED turns ON.
   - Notification is sent via Blynk app.
5. **Reset Condition**: Once IV bag is refilled, the system resets automatically.

---

## 🖼️ Recommended GitHub Folder Structure


---

## 📷 Output Snapshot

Upload the following to the `/output` folder:
- Setup photo
- Serial monitor screenshot
- Blynk app alert view

---

## 🔮 Future Enhancements

The current system delivers accurate and reliable monitoring of IV fluid levels, but there are several compelling directions for future development. These enhancements aim to bring the system closer to real-world deployment in advanced healthcare environments:

- 🏥 **Integration with Hospital Management Systems (HMS/EMR/ERP)**  
  Seamlessly link IV data with hospital ERP platforms for automated record-keeping, real-time alerts to nurses, and centralized patient dashboards.

- 📊 **Real-Time Patient Health Dashboard**  
  A responsive web or mobile dashboard for doctors and caregivers to view live IV stats of multiple patients at once with alert history and health indicators.

- ☁️ **Cloud-Based Logging and Historical Analytics**  
  Automatically back up data to the cloud with support for analyzing trends, patient-specific usage patterns, refill cycles, and predictive maintenance.

- 📲 **Smart Notifications & Multi-Channel Alerts**  
  Add support for SMS, email, WhatsApp, push notifications, and even wearable smart devices (like smartwatches) for faster, targeted alert delivery.

- 🤖 **AI-Driven Predictive Monitoring**  
  Use artificial intelligence to predict when an IV bag will be depleted based on current flow rates, usage patterns, and historical data. Prevents downtime and improves planning.

- 🔋 **Portable Power with Wireless Charging**  
  Incorporate a rechargeable lithium battery with wireless charging support to make the device suitable for mobile carts or ambulance use.

- 🧪 **IV Fluid Quality & Safety Detection**  
  Add advanced sensors for detecting fluid properties such as pH, contamination, or expiry — ensuring patient safety beyond just level monitoring.

- 🔁 **Automated IV Flow Control System**  
  Combine the monitor with a servo valve or smart drip controller to automatically adjust or stop fluid delivery based on sensor feedback.

- 🧬 **Smart Multi-Patient Monitoring Hub**  
  Connect multiple IV systems to a centralized unit that monitors all patient IVs in a ward, reducing the need for individual device checks.

- 📡 **Geo-Fencing for Asset and Patient Safety**  
  Track the device location and usage via GPS or Wi-Fi positioning, helpful for hospitals with multiple departments or remote setups.

- 🗣️ **Voice Assistant Integration (Alexa/Google)**  
  Enable interaction via voice — “What’s the status of bed 4’s IV?”, making it easier for healthcare workers during rounds.

- 🧑‍💻 **Open API for Healthcare Developers**  
  Offer REST or MQTT-based APIs so hospitals can customize or integrate the system with other smart medical devices.

---

## 📄 License

This project is developed for academic and research purposes under the guidance of Ahalia School of Engineering and Technology. You are free to use or extend the project with proper attribution.

