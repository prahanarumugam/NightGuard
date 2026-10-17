# 🌙 NightGuard — Arduino Security Alarm

**NightGuard** is a beginner-friendly Arduino security project that detects movement and sounds an alarm.

## ✨ Features
- Motion detection using an HC-SR501 PIR sensor
- Active buzzer alarm when motion is detected
- Push button to temporarily silence the alarm
- Alarm activates again if motion remains after releasing the button
- Portable power option using a 5V USB power bank

## 🧰 Components
- Arduino UNO R3
- HC-SR501 PIR motion sensor
- Active buzzer module
- Momentary push button
- Jumper wires
- USB cable or 5V USB power bank

## 🔌 Wiring

| Component | Arduino UNO R3 |
|---|---|
| PIR VCC | 5V |
| PIR GND | GND |
| PIR OUT | D2 |
| Buzzer GND | GND |
| Buzzer VCC | 5V, if rated for 5V |
| Buzzer I/O | D8 |
| Push button terminal 1 | D4 |
| Push button terminal 2 | GND |

## ⚙️ How It Works
1. The PIR sensor detects movement.
2. The buzzer sounds when movement is detected.
3. Holding the button silences the buzzer.
4. If movement is still detected after releasing the button, the buzzer sounds again.
5. When movement is no longer detected, the alarm turns off.

## 🚀 Future Improvements
- Bluetooth alerts to a nearby phone
- A custom enclosure
- Battery-powered portable operation

## 🎯 Project Goal
To learn Arduino programming, motion sensing, digital inputs and outputs, and basic electronics through a practical security project.

**Built with curiosity and Arduino!** 🔧
