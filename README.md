# GeloTag 🔊📍

**GeloTag** is a lightweight BLE (Bluetooth Low Energy) tracking device built using an ESP32 SuperMini.  
It works like a minimalist AirTag: when triggered from a smartphone, it activates a buzzer to help you locate it.

---

## 🛠 Features

- Acts as a **BLE server** using the ESP32.
- Waits for incoming commands over Bluetooth (e.g. `"on"` to sound the buzzer).
- Can be controlled from any BLE app, such as **nRF Connect**.
- Useful for locating items like bags, backpacks, toolboxes, or even as a DIY key finder.
