# Voice Assistant ESPHome Tutorial
This repository acts as a companion of the [voice assistant contest launch live stream held on the 17th of January 2024](https://www.youtube.com/watch?v=99lGuB4J-4o)

During this live stream, we created a Voice Assistant based on the ESPHome framework.

If you want to creat your own, chances are you are looking for the code used during the live stream. This repository is here for that!

# Parts
The voice assistant created during the live stream uses the following components:

- [A Feather ESP32 V2](https://learn.adafruit.com/adafruit-esp32-feather-v2)
- An i2s microphone called [INMP441](https://makersportal.com/shop/i2s-mems-microphone-for-raspberry-pi-inmp441)
- An i2s amplifier to drive the speaker called the [MAX98357A](https://learn.adafruit.com/adafruit-max98357-i2s-class-d-mono-amp)
- An a 3W speaker that you can easility find on amazon, here is a link to the [french store](https://amzn.eu/d/frxpQKL)

# The device

The device we created looks like this:
![Device picture](device.png?raw=true "Device Picture")

# Wirring

Here is a detailed view of how we wired the parts:
![Wiring Diagram](wirring.png?raw=true "Wiring Diagram")

# YAML ESPHome Firmware

Here is [the complete YAML Firmware with explanation comments](voice-assistant-prototype.yaml) of what we created together during the stream.

You are free to copy, adapt, and use it however you want.

Have fun building and learning!

JLo
