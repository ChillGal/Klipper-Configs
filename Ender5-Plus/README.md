# Ender 5 Plus

Following modifications from stock
- BigTreeTech Octopus Pro v1.1 (STM32H723)
- HGX Lite2
- BigTreeTech TMC5160T Pro Drivers x8
- NF Crazy Higher Flow Hotend
- Mainboard Noctua A4x10 Fans x3
- PSU Noctua A4x20 Fan
- Hotend Heatbreak cooling Noctua A4x20 Fan
- Additional Power Wires for Motor power

Contains config for following:
|Driver		|Function	|
|:----:		|:----:		|
|Driver 0	|X Stepper	|
|Driver 1	|Y Stepper	|
|Driver 2	|Z0 Stepper	|
|Driver 3	|Z1 Stepper	|
|Driver 4	|Extruder0	|
|Driver 5	|Extruder1	|
|Driver 6	|Unused1	|
|Driver 7	|Unused2	|


Notes:
- Driver 2 has 2 physical connectors on the mainboard that electrically connect to one driver.
- Drivers 6 and 7 are unused but are included in the config for future reference.
- The drivers do not have the stepper rotation direction accounted for in software, Pins for the stepper motor connection cables were swapped to keep the config clean.
