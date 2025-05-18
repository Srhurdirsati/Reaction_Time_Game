# 🕹️ Reaction Timer Game (No Microcontroller)

A pure hardware-based reaction timer game built using transistors, LEDs, resistors, and buttons — **no microcontroller required!**

## 🔧 Features
- 6 LEDs with corresponding push buttons
- When the LED lights up, press its button to "react"
- Runs continuously when battery is inserted
- Simple design, perfect for beginners
- Powered by a CR2032 battery

## 🧰 Components Used
| Component             | Quantity |
|-----------------------|----------|
| 5mm LED (Random Colors) | 6        |
| Push Button (6mm)     | 6        |
| 2N3904 NPN Transistor | 6        |
| 220Ω Resistors        | 6        |
| 4.7kΩ Resistors       | 6        |
| CR2032 Battery & Holder | 1      |

## 🔌 Circuit Logic
Each button triggers its own transistor to switch on an LED. Transistor base current is limited via a 4.7kΩ resistor. LED current is limited by a 220Ω resistor. Power is always ON when battery is inserted.

## 🖨️ PCB Design
Created using EasyEDA. Bottom layer includes personalized artwork/text using SVG on silkscreen.

## 💡 How to Use
1. Insert CR2032 battery.
2. LEDs light up randomly (manual control or toggle externally).
3. Press the corresponding button as fast as possible.
4. Just remove the battery to stop playing.

## 📷 Project Photos 

![Schematic](https://github.com/user-attachments/assets/a915138d-9e1f-4b7e-8db8-e8a6d5d0b0bf)

![PCB](https://github.com/user-attachments/assets/d8fdb0b4-f76a-4639-910c-2fbcdec67481)

![3D View](https://github.com/user-attachments/assets/6c143769-13f7-4366-a03b-b9763257ae6b)

---

Made with 💡 and solder.

Made by **OG._.Rudra** on slack :D

Made as a part of http://solder.hackclub.com/!

