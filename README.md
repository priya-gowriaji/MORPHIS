MORPHIS - Modular Optimised Robotic Platform for Human Inspired Simulation

M.O.R.P.H.I.S. is an animatronic robotic platform designed to replicate lifelike human facial expressions, speech articulation, and interactive response loops using synchronized servo actuation controlled by an onboard NVIDIA Jetson Nano.


Key Features

* Synchronized Facial Actuation: Fine-tuned servo control for real-time jaw and eyebrow movement mapped to speech patterns.
* Voice & Speech Processing:Integrated speech recognition and audio processing pipeline.
* Modular Hardware Architecture: Scalable setup using I2C/PWM drivers for low-latency motor control.
* Edge Computing Ready: Designed to execute on the NVIDIA Jetson Nano platform.

System Architecture & Hardware

 Core Hardware
* Main Controller: NVIDIA Jetson Nano
* Servo Driver: PCA9685 16-Channel 12-bit PWM I2C Driver
* Actuators: High-precision micro servos (Jaw articulation & Eyebrow expressiveness)
* Power Supply: Dedicated 5V external DC power for servos



Quick Start

 1. Prerequisites
Ensure your Jetson Nano is flashed with JetPack and connected to your local network/peripherals.

bash
# Update system dependencies
sudo apt-get update && sudo apt-get install -y python3-pip i2c-tools
