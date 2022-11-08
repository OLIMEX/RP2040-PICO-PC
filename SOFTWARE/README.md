Software examples for Olimex RP2040-PICO-PC and Raspberry Pi Pico

Folder "no-OS-FatFS-SD-SPI-RPi-Pico" contains SD card example, the project was adapted for RP2040-PICO-PC using this one:

https://github.com/carlk3/no-OS-FatFS-SD-SPI-RPi-Pico

Folder "PicoDVI" contains DVI example, the project is made after this one:

https://github.com/Wren6991/PicoDVI

Folder "pico-pwm-audio" contains audio examle, the project is based on this one:

https://github.com/rgrosset/pico-pwm-audio

Folder "Prebuilt-UF2" contains prebuilt binaries for each of the three projects.

The environment to build the projects was configured accordind to the getting-started-with-pico.pdf guide:

https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf

If you don't want to bother with building just use the prebuilt UF2 files, connect the Raspberry Pi Pico to your computer using a micro-USB cable, making sure that you hold down the BOOTSEL button to force it into USB Mass Storage Mode. The board should automatically appear as a external drive. You can now drag-and-drop the UF2 binary onto the external drive.
