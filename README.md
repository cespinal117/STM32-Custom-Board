# STM32-Custom-Board

This is a board I decided to create to practice my PCB Design skills.  

I chose the STM32 as the main MCU due to me wanting to learn the STM32 platform.

My main motivation for the features of this board is that throughout college I mostly worked on projects involved Servo motors. Instead of having a separate Servo driver board with more wires, I thought it would be nice to have it all embedded into a single PCB that will power and control everything.  
The ESP32 was a last second addition as I thought it would be cool to be able to control the motors wirelessly through a web interface or bluetooth.

# Features
- STM32 MCU as the main processor
- ESP32 for wireless capabitlities
- PCA9685 Servo driver
- Switching between 5V USB or external 5V (prioritizes USB for the MCU if plugged in)

![Screenshot](/screenshots/schematic.png)

![Screenshot](/screenshots/layout.png)
![Screenshot](/screenshots/3dview.png)
