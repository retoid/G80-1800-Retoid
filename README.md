# G80-1800
Making a custom PCB for Cherry G80-1800 with hotswap socket compatibility.

This is a customized version of evyd13's files found here: [GH80-1800](https://github.com/evyd13/gh80-series/tree/master/GH80-1800)

**Note!** I have removed the alternate positioning for varying layouts and included support for Kailh or Gateron Hotswap sockets. The firmware supports only this layout.
The PCB supports PCB or Plate mount switches. However the Plate file supports only PCB mount stabilizers.
Must use hotswap sockets, otherwise you will have to change the switch footprints to accept solder mount.

**Versions** V1.0 uses a different layout that utilizes a 6U Cherry Spacebar. But since these are rather difficult to come by, both 6U spacebar and 6U stabilizers. The updated V1.1 utilizes a 6.25U spacebar but eliminates a key and changes some key sizes on each side of the spacebar. V1.0 does not have the PCB mount support holes for switches.

**Project Files** are created with KiCad.
Version: (5.99.0-7511-ga134567838), release build


## BOM

| LCSC part #   | Description   | Value | Package  | Amount |
| -----------   | ------------- | ----- | -------- | ------:|
| C128353       | Capacitor     | 0.1uF | 0805     | 4      |
| C131056       | Capacitor     | 4.7uF | 0805     | 1      |
| C215803       | Capacitor     | 1uF   | 0805     | 1      |
| C109001       | Diode         |       | 0805     | 108    |
| C105424       | Connector     |       | SMD      | 3      |
| C103904       | Resistor      | 10K   | 0805     | 2      |
| C384174       | Resistor      | 1K    | 0805     | 3      |
| C325772       | Resistor      | 22    | 0805     | 2      |
| C44854        | MCU           | 32U4  | QFP-44   | 1      |
| C341521       | Resonator     | 16MHz | SMD      | 1      |
| C92584        | Switch        |       | SMD      | 1      |
|               |               |       |          |        |
| Kailh/Gateron | Hotswap socket|       | SMD      | 108    |
