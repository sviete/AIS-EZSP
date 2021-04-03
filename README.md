# Ebyte E180-ZG120B


## Info:

Module EFR32MG1B232F256GM48


- M - family code
- G - Gecko
- 1 - series 1
- B - type: P (Performance), B (Basic), V (Value)
- 2 - Feature Code reserved
- 3 - Feature Code TXRX
- 2 - Feature Code Band 2.4GHz
- F256 — Flash 256K


||MG1B232F256GM48|
---------|------------------
MCU Core |	ARM Cortex-M4
Core Frequency (MHz) |	40
RAM (Kb)	|	32
Flash (Kb)|	256
Tx (dBm) |19.5
Rx (dBm) |-101


Full DataSheets:
https://www.silabs.com/wireless/zigbee/efr32mg21-series-2-socs/device.efr32mg21a020f768im32


## Flashing

To flash Ebyte E180-ZG120B module we need to load the bootloader first.
To do this you need:
- SWD Flasher (I used Jlink programmer from SEGGER)
- Simplicity Commander (Linux version is in this repo in tools folder)
- firmware bootloadera (in this repo file BTL_STD_MG1B232_TX-PA0_RX-PA1_BT-PB11-combined.s37)

Connection:

|Jlink|Ebyte|
|-----|-----|
VTref | VCC
  GND | GND
SWDIO | SWO
SWCLK | SWK


Simplicity Commander - connection to Ebyte via Jlink:
