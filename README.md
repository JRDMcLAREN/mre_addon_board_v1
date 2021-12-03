# mre_addon_board_v1

Addon board for microrusEFI ECU.
Wideband controller wiring is based on https://github.com/mck1117/wideband, official rusEFI wideband controller.
This is version for STM32F042K6Tx MCU in LQFP32 package.

This addon board has build rusEFI wideband controller, microSD card slot and K-Thermocouple controller.
It can be used on all MRE with appropriate connector headers.

Wideband controller require CAN bus connectivity and additional power supply form 12MREL pin (pre R0.5.5rc) for sensor heater.
LSU 4.9 sensor wires are connected via MOLEX MicroFit 3x2 connector 43045-0601 or 43045-0612
K-Thermocouple wires are connected via MOLEX MicroFit 2x1 connector 43045-0202 or 43045-0212

![wideband_controller_mre](https://github.com/JRDMcLAREN/wideband_controller_mre/blob/main/wideband_controller_mre.jpg)
