# ISPBoard

This repo contains a project with a programming board for Atmel 28 DIP that can
be programmed using a 6-pin JTAG port (ISP). It is designed specifically for use
with ATmega 328P dip package.

# Software
For this project, the following software is used:

- KiCad
- Solid Edge

# Revisions

## Rev 1
External power needed. Test ports for leds, buttons and 2 pins from each pin
register.

## Rev 2
__Moved to this separate repo.__ 

Added battery power via a 9-5V DCDC converter. Improved layout. Added a port for
USART output. Added a 3D-printed case for the PCB.


# Future (potential) improvements

- USART output via FTDI chip to USB contact.
