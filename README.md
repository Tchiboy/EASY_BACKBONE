# EASY_BACKBONE
How to get the backbone running of the Energy Analysis Sensor-it Yourself, EASY, project. After following the steps in this guide you will have:
- A hardware Hub that's installed with Home Assistant
- A running Home Assistant dashboard
- (Optional) Power usage of a whole household and single devices

# Hardware
- Hardware hub, (e.g. ODroid M1, OrangiPi 5)
  - 12V DC Power Supply (Barrel Plug)
  - Ethernet Cable
- Smart plug (optional)
  - [The used smart plug](https://tweakers.net/pricewatch/1734452/shelly-plug-s-1-pack.html) 
- P1 reader (optional)
  - [The used open source P1 reader](https://www.zuidwijk.com/product/slimmelezer-plus/)

# Hardware Hub installation
## Home Assistant installation methods
Home Assistant has a couple installation methods. The biggest difference between these methods is the addition of the ["Add-on store"](https://www.home-assistant.io/addons). The Add-on store can be used to quickly install additional software/applications to the Home Assistant installation. The first prototype (ODroid M1) used this Home Assistant OS, this is because of the addition of the add-on store and general ease of use. To install a containered, Core or Supervised installation, the hardware hub needs an installed Linux Distro (preferably Ubuntu or Debian/Armbian).  

![image](https://github.com/Tchiboy/EASY_BACKBONE/assets/77402736/3617848a-e43d-4fdf-859d-7c8f52a6acc7)

## Installation
Use the installation page of Home Assistant to get the most up-to-date images and more information regarding installation. Which images (and method of installation) you need depends on the used hardware. 

[Installation page of Home Assistant]([url](https://www.home-assistant.io/installation/))

### ODroid
ODroid hardware is directly supported by the Home Assistant community. This means that there is a Home Assistant OS image available. It's also possible to use the generic Linux installation. 

[ODroid M1 Home Assistant OS image ]([url](https://github.com/home-assistant/operating-system/releases/download/11.1/haos_odroid-m1-11.1.img.xz))

### OrangePi 5
The OrangePi 5 isn't directly supported by the Home Assistant community, so there is **no** official Home Assistant OS image available. The best option is to flash the OrangePi 5 with a (supported) Linux distro and run Home Assistant containered, or use Virtual Machine software to run Home Assistant OS.

[OrangePi 5 Supported Linux distro download page]([url](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-pi-5.html))
[Guide for installing Home Assistant Containered on an OrangePi 5 ]([url](https://gist.github.com/renatoccosta/c30f0b4216c8caaf1f202b0a0561b5d3))

### Rock64
The Rock64 isn't directly supported by Home Assistant community, so there is **no** official Home Assistant OS image available. The best option is to flash the Rock64 with a (supported) Linux distro and run Home Assistant containered, or use Virtual Machine software to run Home Assistant OS.

[Rock64 supported Linux distro wiki page]([url](https://wiki.pine64.org/wiki/ROCK64_Software_Releases))

# Installation of optional hardware
## Smart Plug (individual power reading)
[Video guide: how to install the Shelly Plug S (Smart Plug) in Home Assistant]([url](https://youtube.com/watch?v=Q4kuJEhYBa8))
## P1 reader (house-wide power reading)[
Text guide: how to install the P1 reader in Home Assistant]([url](https://www.zuidwijk.com/initial-setup-slimmelezer/)
