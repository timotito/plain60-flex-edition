# Plain60 Flex Edition rev2.2.1
This is an independently developed branch of the Plain60 Flex Edition, by evyd13.

![Plain60 Flex Edition PCB](https://i.imgur.com/nfs9vOc.png)
This universal 60% PCB is designed to support as little layouts as possible without limiting usability for most users. The reason evyd13 did this is because other PCBs made for this form factor usually have so many supported layouts that it could almost qualify as swiss cheese.

It also features a fuse and an ESD protection chip to protect the MCU and other parts of the PCB.

## Features
- Fits in the TGR Unikorn
- Compatible with QMK Firmware and VIA Configurator (if you flash a VIA compatible .hex file)
- Compatible with most universal 60% cases and HHKB/WKL Tofu by KBDfans
- USB type-C
- Optional JST header for connection with daughterboard
- Footprint for optional speaker (AST1109MLTRQ)
- ESD protection and fuse
- No LEDs and no underglow
- Minimal layout support
- ISP header

## Supported layouts
![Supported layouts of the Plain60-C](https://i.imgur.com/dq04Csv.png)

## Building
If you feel like building a few of these PCBs yourself, the required gerber files are in the named folder. Order those at your favourite PCB manufacturer, get the components needed (see included BOM) and solder them on! Alternatively, request SMT assembly from the manufacturer.

A hot air station is not required but a soldering iron is. Flux is recommended.

## Opening the project
To open the files you will need KiCAD.
