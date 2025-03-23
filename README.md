LFR Bot Using 3 IR Sensors, Motor Driver (L298D), and Arduino Uno

Overview

This repository contains the code and instructions to build a Line Follower Robot (LFR) using 3 IR sensors, an L298D motor driver, and an Arduino Uno. The robot detects a black line on a white surface and follows it autonomously.

Components Required

Arduino Uno (Main controller)

L298D Motor Driver (Controls motors)

3 IR Sensors (Detects the line)

2 DC Motors (For movement)

Chassis (Base structure)

Wheels (For mobility)

Power Supply (9V or 12V battery)

Jumper Wires (For wiring connections)

Circuit Diagram



Circuit Connections

IR Sensors to Arduino:

Left Sensor → 7

Middle Sensor → 8

Right Sensor → 9

Motor Driver (L298D) to Arduino:

Motor 1 (Left Motor)

IN1 → Pin 5

IN2 → Pin 6

ENA → 2

Motor 2 (Right Motor)

IN3 → Pin 10

IN4 → Pin 11

ENB → 3

Power Connections:

L298D VCC → 9V Battery

L298D GND → Arduino GND

L298D 5V Output → Arduino 5V
