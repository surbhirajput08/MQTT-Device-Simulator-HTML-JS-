# 🛰️ MQTT Device Simulator (HTML + JS)
CI/CD Pipeline
> ⚡ **MQTT Device Simulator — connect, publish, and test IoT data instantly in your browser 🌐.**

A lightweight, browser-based MQTT device simulator built using the **Paho MQTT JavaScript client**.  
This single HTML file allows you to **connect, publish, subscribe, and visualize simulated IoT device data** — perfect for testing brokers, MQTT payloads, or IoT dashboards.

---

## 🚀 Features

✅ **No installation required** — just open the `.html` file in any modern browser.  
✅ **Connect to any MQTT broker** using `ws` or `wss` (WebSocket) protocol.  
✅ **Simulate device telemetry** (temperature, humidity, etc.) with editable fields.  
✅ **Auto-publish mode** for periodic simulation of live IoT data.  
✅ **Subscribe and view messages** from any topic in real time.  
✅ **Visual-ready data** — automatically stored in `localStorage` for future graphing.  
✅ **Modern responsive UI** — built with clean CSS and a card-based layout.  

---

## 🧩 How to Use

1. **Open** the `Mqtt Publisher Device Simulator.html` file in your browser or upload it to [CodePen](https://codepen.io/zhadowvalker/full/MYKomVN).  
2. **Configure your MQTT broker:**
   - 🖥️ **Host:** e.g. `broker.hivemq.com`
   - ⚙️ **Port:** `8883` for `wss`, or `8083` for `ws`
   - 🔐 **Protocol:** `wss` (secure) or `ws`
   - 📁 **Path:** usually `/mqtt`
   - 👤 **Credentials:** optional username & password
3. Click **🔌 Connect** to establish the connection.  
4. Use **📡 Send** to publish data manually.  
5. Use **🚀 Start Auto** to simulate continuous device telemetry.  
6. View logs and subscribed topic messages in real time.  

---

## 🧠 Example Configuration

| Field | Example |
|-------|----------|
| **Host** | `192.168.0.0` |
| **Port** | `8883` |
| **Protocol** | `wss` |
| **Path** | `/mqtt` |
| **Username** | `iot` |
| **Password** | `iot` |
| **Topic** | `devices/data` |

---

## 📊 Optional Graphing

All received messages are stored in the browser’s local storage (`mqttDeviceData`).  
You can open `graph.html` to visualize temperature and humidity trends over time for each device.

---

## 🧱 Technologies Used

- 🧩 **HTML5** + **Vanilla JavaScript**
- 🎨 **CSS3** (custom styling, no frameworks)
- 🔗 **[Paho MQTT JS client v1.1.0](https://unpkg.com/paho-mqtt@1.1.0/paho-mqtt-min.js)**

---

## 🧪 Ideal For

- 🧠 MQTT broker testing (`Mosquitto`, `HiveMQ`, `EMQX`, etc.)  
- 🌡️ IoT sensor data simulation  
- 🎓 Educational demos and workshops  
- 🧰 Debugging MQTT topics and payloads quickly  

---

## 📝 License

This project is released under the **MIT License**.  
Feel free to **fork**, **modify**, and **experiment** for your own IoT or MQTT testing needs.

---

### 🌟 Author

Developed by **ZhadowValker**  
💻 For learning, testing, and edge IoT simulation scenarios.

---
