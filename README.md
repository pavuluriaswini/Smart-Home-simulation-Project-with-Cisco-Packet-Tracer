# 🏠 Smart Home Simulation Project using Cisco Packet Tracer

This project demonstrates a Smart Home network simulation designed and implemented using **Cisco Packet Tracer**. It simulates the working of various IoT devices connected to a wireless network, managed through an IoT server, and controlled via a centralized web interface.

## 📌 Project Overview

The simulation models a home automation system with several smart devices such as:

- 💡 Light
- ❄️ Air Conditioner
- 🌬️ Fan
- 🚪 Door Lock
- 🚗 Garage Door
- 💧 Humidity Sensor

All devices are registered and managed through an **IoT Server**, which provides a web-based dashboard for control and monitoring.

---

## 🧩 Network Topology

### 🔹 Devices Used:

- **HomeRouter-PT-AC** (Wireless Router)
- **PC-PT** (Control PC)
- **Laptop-PT** (Optional mobile control)
- **Smartphone-PT** (Optional mobile control)
- **2901 Router**
- **2960-24TT Switch**
- **Server-PT** (IoT Server)
- **IoT Devices**: AC, Fan, Light, Door Lock, Garage Door, Humidity Monitor

### 🔹 IP Addressing:

| Device        | IP Address     | Subnet     |
|---------------|----------------|------------|
| Home Network  | 10.1.1.0/24    | /24        |
| IoT Server    | 10.1.2.2       | 10.1.2.0/24 |
| PC            | DHCP (from HomeRouter) | 10.1.1.x |

---

## 🔧 Configuration Steps

1. **Set up DHCP** on the wireless router for automatic IP assignment to client devices.
2. **Connect and configure** all IoT devices to the wireless router.
3. **Set static IP** for the IoT Server (10.1.2.2).
4. **Enable HTTP** on the IoT Server to allow web-based device control.
5. **Register IoT devices** using PC browser at `http://10.1.2.2`.
6. **Control devices** and monitor humidity via the server interface.

---

## 🌐 Functional Demonstration

- ✅ Devices can be switched **ON/OFF** from the web dashboard.
- ✅ Humidity is displayed in real-time from the sensor.
- ✅ The PC receives its IP address via DHCP (as shown in configuration).
- ✅ Devices communicate across networks through router setup.

---



## 📁 Files

- `Home IOT.pkt`: Main Cisco Packet Tracer simulation file
- `README.md`: Project documentation

---

## ✅ Future Improvements

- Add automation based on sensor thresholds (e.g., auto-turn on AC when humidity > 70%)
- Implement password protection and user authentication on the IoT server
- Add remote access simulation via external network






