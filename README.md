### Introduction
These projects are assembled from some parts like ESP32, some steppers, and a pack of [openbuilds](https://openbuilds.com/) alu profiles and accessories. All of them somehow control stepper motors with ESP32 via Wi-Fi
 
### Hardware
Еhe projects use a **ESP32-Wroom *38-pin*** board 

![wroom](https://github.com/workstarovoitov/stepperControlNodeMCU/blob/main/.github/images/wroom.jpeg)

with this [shield](https://oshwlab.com/starovoitov/nodemcuStepperShield)

![shield](https://github.com/workstarovoitov/stepperControlNodeMCU/blob/main/.github/images/shield.jpg)

### Software
This project uses the source code of the [GRBL for the ESP32](https://github.com/bdring/Grbl_Esp32)

### HINTS
* So that the device receives the IP address automatically the **AP Static IP** should not matches your DHCP server IP
* If somth go wrong with WebUI or you need to clear nodeMCU memory use [Flash download tool](https://www.espressif.com/en/support/download/other-tools)


## Motorized mic stand
![micStand](https://github.com/workstarovoitov/stepperControlNodeMCU/blob/main/.github/images/micStand.jpg)

Some details you may find [here](https://openbuilds.com/builds/motorized-mic-stand.9755)

## Laser engraver
![laserCNC](https://github.com/workstarovoitov/stepperControlNodeMCU/blob/main/.github/images/laserCNC.png)

Some details you may find [here](https://openbuilds.com/builds/laser-engraver.9811)
