# 🔌 NANOSWITCH PRO

🌐 *Baca dalam [Bahasa Indonesia](README.md)*

![Version](https://img.shields.io/badge/version-2.5%20Pro-e08b26)
![Platform](https://img.shields.io/badge/platform-ESP8266%20%7C%20Wemos%20D1%20Mini-00384c)
![License](https://img.shields.io/badge/license-MIT-blue)

**NANOSWITCH PRO** is a Wi-Fi-based smart switch control system built on the ESP8266 (Wemos D1 Mini) microcontroller. This system allows you to remotely control household appliances via an interactive Web Dashboard or physical wall switches without requiring an internet connection.

---

## ⚡ Quick Installation (No Arduino IDE Needed!)

> 💡 **Great News!** You **don't need to hassle** with installing Arduino IDE, setting up libraries, or compiling `.ino` source code files manually.
> 
> Pre-compiled **Firmware Binary (`.bin`)** files ready for flashing are provided in two languages:
> - 🇮🇩 **Bahasa Indonesia**
> - 🇬🇧 **English**

### How to Flash Pre-compiled Firmware (`.bin`):

1. Download the latest `.bin` file from the [Releases](../../releases) section of this repository in your preferred language (`firmware_id.bin` or `firmware_en.bin`).
2. Connect your Wemos D1 Mini / ESP8266 to your PC via a Micro-USB Data cable.
3. Open your flasher tool of choice (e.g., **NodeMCU PyFlasher**, **ESP Web Flasher** via Chrome, or **NodeMCU Flasher**).
4. Select your board's COM Port, choose the downloaded `.bin` file, and click **Flash**.
5. Done! Your device is ready to use.

---

## 💻 Manual Build Option (For Developers)

If you wish to modify or customize the source code:

1. Open the `.ino` file located inside `/firmware/nanoswitch_id/` or `/firmware/nanoswitch_en/`.
2. Use Arduino IDE with the ESP8266 board package installed.
3. Ensure `ESP8266WiFi`, `ESP8266WebServer`, `DNSServer`, `LittleFS`, and `ArduinoJson` v6.x libraries are installed.
4. Upload the sketch to your ESP8266 board.

---

## 🛠️ Specifications & Pinout

| Component | Specification / Notes |
| :--- | :--- |
| **Microcontroller** | ESP8266 Wemos D1 Mini |
| **Storage System** | LittleFS |
| **Default SSID** | `NANOSWITCH PRO` |
| **Max Relays** | 8 Channels |

| Pin Label | ESP8266 GPIO | Default Usage |
| :---: | :---: | :--- |
| **D1** | GPIO5 | Relay Output 1 |
| **D2** | GPIO4 | Push Button Input 1 |

---

## 👨‍💻 Developer

Developed by:
- **Developer:** `Andre_Aryafin069`

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
