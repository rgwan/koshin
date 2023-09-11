# Koshin
Cheap and steady STM32F103 based debug probe with SWOTRACE and serial ports (WIP). It has built-in level-shifter to support target voltage from 1.8V - 5.5V.

Firmware will be based on (devanlai/dap42), with some enhancement (serial port, MCO, TRACE, isolator-ready and so on).

# Hardware Status

- [x] Initial version of Hardware
- [ ] Hardware freeze (stable release)
- [ ] Isolator expansion board
- [ ] SPI Flash and 24 EEPROM programmer expansion board
- [ ] 0.95 - 3.3V level shifter expansion board for ultra low-voltage systems

# Firmware Status

- [x] Bootloader (devanlai/dapboot)
- [x] Beeper and LEDs
- [ ] CMSIS-DAP
- [ ] USB CDC-ACM serial port
- [ ] MPSCQ (Multi-Protocol Serial Command Queue) based fast USB to (JTAG/SPI/I2C and IEEE 1149.7 support)

# Links

- Bootloader (WIP): <https://github.com/rgwan/dapboot>
- Firmware (WIP): <https://github.com/rgwan/dap42>

# License
GPLv3 for schematics.
