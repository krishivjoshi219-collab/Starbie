# Starbie — Straw Hat Edition

A custom pirate-themed interactive virtual pet console and environmental monitor powered by the Seeed Studio XIAO ESP32-C3 (based on the starbie)
so basically I don't how to write a readme.dm so it might be um worst :C 
---
## Images

![PCB Editor](assets/PCB_Editor.png)

![Schemetic Editor](assets/Screenshot_from_2026-10-11_17-09-22.png)

![3D Front view](assets/Screenshot_from_2026-10-11_17-15-12.png)

![3D Back view](assets/Screenshot_from_2026-10-11_17-15-34.png)

---

## Hardware Features
Here we hard following components:
Mircrocontroller: I used a ESP32-C3 (I am new do i don't know much about mircrocontroller!!!!!)

Display: I used a 4 pin 0.96 OLED for displaying my luffy (i know that luffy is not a pet but uh whatever)

Push BUttons: I wired 2 push button on the side of the PCB so you can open the menu etc

Motion sensors: So luffy can react to any motion like falling etc

Temperature: Just shows the tempeature in the menu 

---

## Hardware Pinout

| Function / Component | XIAO Pin Label | ESP32-C3 GPIO | Notes |
| :--- | :--- | :--- | :--- |
| **DHT11 Data** | D0 | GPIO 2 | 10kΩ pull-up to +3.3V |
| **Button 1 (Menu)** | D2 | GPIO 4 | Active-Low (Internal Pull-Up) |
| **Button 2 (Stats)** | D3 | GPIO 5 | Active-Low (Internal Pull-Up) |
| **I2C SDA** | D4 | GPIO 6 | Shared by OLED and MPU-6050 |
| **I2C SCL** | D5 | GPIO 7 | Shared by OLED and MPU-6050 |
| **Buzzer Driver** | D6 | GPIO 21 | Switches NPN base via 1kΩ resistor |

---


---

## Firmware Setup

1. Install the Arduino IDE grant it permission to run it
2. open `firmware/Starbie/Starbie.ino` in the Arduino IDE.
3. Install the board in the IDE (esp32 by espreesif system)
 Select **XIAO_ESP32C3** under **Tools → Board → esp32**.
4. IInstall the following via Library Manager:
   * `Adafruit GFX Library`
   * `Adafruit SSD1306`
   * `Adafruit MPU6050`
   * `DHT sensor library`
5. code is already compiling (i just used the starbie frimware from the guide !!!)
6. Make sure that your microcontroller is connected to a USB 3 and push the code and BOOM!! your starbie is ready (provided that you already made the circut on a PCB!!)

---
## How I made It !
First of all i am a beginner who is doing his first hardware project and first project without the use of AI (exluding writng C++ in the arduino IDE it is well under the 30% ai limit)

This is the first time i am writing a README.md !! 

I was seriously like oh i could even do all this !! when i first opened the kicad for half life

Half Life is my first ysws and first project in which use of ai was minimal but still it was hard for me !!

But it was really fun too !!
I started this week late just on wed and that also cuz of schools etc i was busy right now too!!

KiCAD is now really easy for me it doesn't feel like a new world now !!:D 

But i had many dificuties too very much so this time instead of vibe coding i did everything myself just took help of the ai by asking questions like "How to do this ?" etc but i did the entire designing part myself and also i was really scarded like just how to write a README !!!!!!!!

But now it feels easy !!

And also i am able to explain the entire project myself !

---
# Most Boring parts

What i found most boring was adding silkscreen !!
Other than it i enjoyed everything most of ig

And solving the errors in the PCB design was the most frustating part !!! that 64nm error i talked about in my journal !!

---
# Most Fun part
Most fun part as PCB routing and adding the edge.cuts as the straw hats !!!!!!!!!!

After that i enjoyed the schemetic too and i generally enjoyed the debugging the KiCad errors too !

---
## At last I want to thanks the hc ysws half life organizers for organizing such a great ysws and giving me the opportinity to learn !!