# NightGuard — Arduino Motion Alarm

NightGuard is an Arduino-based prototype that detects movement and activates an alarm.

## Features
- Motion detection using an HC-SR501 PIR sensor
- Relay module used to switch the alarm
- Separate battery supply for the alarm circuit
- DC ON/OFF switch for the alarm power
- No silence push button in the current design

## Components
- Arduino UNO R3
- HC-SR501 PIR motion sensor
- 1-channel 5V relay module
- Wired alarm/buzzer
- Battery and battery connector for the alarm supply
- DC ON/OFF switch
- Jumper wires

## Current Design
The PIR sensor provides the motion signal to the Arduino. The Arduino controls the relay module, which switches the separate alarm circuit. The DC switch is used to turn the alarm supply on or off.

**Note:** This README describes the current prototype at a high level. Check the ratings printed on the alarm and power components before wiring or powering the circuit.

## What I'm Learning
- Reading motion sensor signals
- Controlling a relay with an Arduino
- Separating a control circuit from a switched load
- Building and documenting electronics projects

NightGuard is a learning project and is still being developed.
