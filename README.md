# mre_addon_board_v1

Addon board for microrusEFI ECU.
Wideband controller wiring is based on https://github.com/mck1117/wideband, official rusEFI wideband controller.
This is a version using STM32F042K6Tx MCU in LQFP32 package.

This addon board has build-in rusEFI wideband controller, microSD card slot and K-Thermocouple controller.
It can be used on all MRE with appropriate connector headers.

Wideband controller requires 
* CAN bus connectivity 
* additional power supply from 12V_MREL pin for sensor heater.
(not required for "my" MRE versions - R0.5.5rc, R0.6.1rc)

LSU 4.9 sensor wires are connected via MOLEX MicroFit 3x2 connector 43045-0601 or 43045-0612
K-Thermocouple wires are connected via MOLEX MicroFit 2x1 connector 43045-0202 or 43045-0212

SPI ChipSelect CS# pins:
PA15 - for EGT chip
PB9 - for microSD card

![wideband_controller_mre](https://github.com/JRDMcLAREN/wideband_controller_mre/blob/main/wideband_controller_mre.jpg)
