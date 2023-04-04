# No Command Continuous Voltage Reading

DA14531 code built on the ble_app_peripheral template. Adjustment of the ble_app_peripheral ADC functionality with the Control Point characteristic to use solely the ADC 1 Value characteristic, reading values on notification enabling without the need for a command to begin readings.

Current setup has readings saved as uint16_t (unsigned 16-bit integer) type and sent as an array in a packet.

These files are protected under copyright by Renesas Electronics, formerly under Dialog Semiconductor. This repository does not claim ownership or authorship to the files contained within.
