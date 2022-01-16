# Liquid-level-switch-with-IR-liquid-level-sensor
This repo shows, how to build a liquid level switch by using an IR level sensor.

An IR liquid level sensor works similar to an IR light barrier, with a transparent plastic hood. When the sensor comes into contact with liquid, the refraction at the interface changes, and with it the strength of the reflected IR beam. It can detect almost any liquid type, oil or water based, and is suitable for harsh environments.
The advantage of this sensor is the high accuracy, usually ±1mm, and the robustness, and of course the low price. The disadvantage is that it can only measure at one point, but not continuously.

![functionality](https://user-images.githubusercontent.com/13086712/149655507-c1d05e1d-40a1-48ab-b45c-3c87add3886c.jpg)
 
The here described circuit can be used in many situations, e.g. for level measurement or as a leak detector.
The circuit of the level switch is quite simple. The output signal at pin2 of the sensor (P3) is amplified by transistor Q1. The transistor Q1 is turned on, as soon as the output goes from LOW to HIGH, and the relay toggles. It is supplied with 5V DC at P2.

![LLS-schematic](https://user-images.githubusercontent.com/13086712/149655485-fafa1dfe-5db6-492c-a68d-a6d336e9eaad.png)

Schematic

![1920f3d5-d17a-44ac-9c86-2cddb7decd49](https://user-images.githubusercontent.com/13086712/149657597-217ac068-f011-4d92-b168-ad7964de6fa1.jpg)

![O1CN01kIo1AF1vNmlV769mU_!!645606161](https://user-images.githubusercontent.com/13086712/149656416-9ef60c28-80cb-46a7-bdeb-2a7fc0aacf0c.jpg)
