# Air Signature Authentication using ESP32 and TinyML

## IEEE Publication

This project has been published in the **2025 Second International Conference on Intelligent Technologies for Sustainable Electric and Communications Systems (iTech SECOM), IEEE**.

**Paper Title:** *Sensing In-Air Signature Motions with ESP32-Embedded Pen: A Privacy-Preserving Approach to Behavioural Authentication*

## Overview

This project presents a privacy-preserving behavioural authentication system that recognizes users through in-air signatures using an ESP32-based embedded pen. Motion data is captured using an MPU6050 IMU sensor and processed locally using TinyML for secure, low-latency authentication.

## Key Features

- ESP32-WROOM-32 based embedded system
- MPU6050 6-axis IMU sensor
- TinyML model trained using Edge Impulse
- On-device inference using TensorFlow Lite Micro
- ESP-NOW communication
- AES-128 encrypted authentication
- Offline authentication
- 96.2% classification accuracy

## Hardware

- ESP32-WROOM-32
- MPU6050 IMU
- Embedded Pen Prototype

## Software

- Arduino IDE
- Edge Impulse
- TensorFlow Lite Micro
- C++
- ESP-NOW

## Results

- Accuracy: **96.2%**
- Average authentication latency: **187 ms**
- Supports **5 registered users**
- IEEE Published (2025)
