# Part 4 – Raspberry Pi Hardware Identification
Upload:
```
images/raspberry-pi/pi-board.jpg
images/raspberry-pi/labelled-pi-board.jpg
```
---

| Component | Function |
|-----------|----------|
| SoC | System on Chip – combines the CPU, GPU, and memory controller on a single chip to run the operating system and programs. |
| GPIO | General Purpose Input/Output pins that let the Pi connect to and control external electronics such as LEDs, sensors, and motors. |
| USB | Universal Serial Bus ports for connecting peripherals like keyboards, mice, and storage devices. |
| HDMI | High-Definition Multimedia Interface output that carries digital video and audio to a monitor or TV. |
| Power | Micro-USB/USB-C connector that supplies power to the board (typically 5 V). |
| microSD | Slot holding the microSD card that stores the operating system and user files as the Pi's main storage. |
| Network | Ethernet port for a wired connection to a local network or the internet. |
| Wireless | Built-in Wi-Fi and Bluetooth for wireless networking and connecting to other devices. |

---
## Reflection
Why are many components integrated into a single board in embedded computers such as the Raspberry Pi?
Write **100 words**.

Embedded computers such as the Raspberry Pi integrate many components onto a single board to reduce size, cost, and power consumption. Combining the CPU, GPU, memory controller, networking, and I/O into one SoC removes the need for separate expansion cards and long internal cables, which makes the device smaller and more reliable because there are fewer connections that can fail. A single board also simplifies manufacturing and lowers production costs, allowing the Pi to be affordable for education and hobby projects. In addition, shorter signal paths between components improve speed and energy efficiency, which is important for devices that must run continuously on low power.