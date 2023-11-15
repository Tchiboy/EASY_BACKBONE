# EASY_BACKBONE
How to get the backbone running of the Energy Analysis Sensor-it Yourself, EASY, project. After following this guide you will get the following product:
- Hardware Hub installed with Home Automation software
- A running dashboard
- Energy insight

# Hardware
- Hardware hub, (e.g. ODroid M1, OrangiPi 5)
  - 12V DC Power Supply (Barrel Plug)
  - Ethernet Cable
- Smart plug (optional
- P1 reader (optional)

# Flashing
## Installation + methods
Use the installation page of Home Assistant to get the most up-to-date images. Which images (and method of installation) you need depends on the used hardware. Some Single Board Computers (SBC's) aren't supported by Home Assistant, so they don't have a specific Home Assistant OS Image. The next best option is to use Home Assistant container, Core or Supervised. 

General installation page of Home Assistant: https://www.home-assistant.io/installation/

![image](https://github.com/Tchiboy/EASY_BACKBONE/assets/77402736/3617848a-e43d-4fdf-859d-7c8f52a6acc7)

### ODroid
ODroid hardware is directly supported by the Home Assistant community. This means that there is a Home Assistant OS image available. 
ODroid M1: https://github.com/home-assistant/operating-system/releases/download/11.1/haos_odroid-m1-11.1.img.xz

### OrangePi 5
The OrangePi 5 isn't directly supported by Home Assistant. so running the Home Assistant Operating System is **not** possible. 
Use the following guide to install Home Assistant Containered on an OrangePi 5: https://gist.github.com/renatoccosta/c30f0b4216c8caaf1f202b0a0561b5d3

### Rock64
The Rock64 isn't directly supported by Home Assistant, so running the Home Assistant Operating System is **not** possible. 
