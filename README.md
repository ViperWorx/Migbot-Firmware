# Ax's Migbot Prusa i3 Firmware
This is a preconfigured version of the firmware for the Migbot Prusa i3. This has been done as the default firmware is junk and is totally wrong for these Acrylic framed printers. 

Use Arduino IDE 1.6 to upload all firmware as previous versions of the Arduino software had a bug in the compiler.

The 1.1 firmware allows for the Extruder fan (the one with the heatsink) to be connected to E1 on the MKS board. The fan will switch on at 50c when the hotend is heating and off when cooling down. This extends fan life and keeps the printer quiet when it is not printing. 
