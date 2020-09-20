# avr-libs
madcatdev AVR Libraries

This is a bunch of libraries for AVR MCUs (currently Atmega168/328(p)).
It was created to simpify my work with bare-metal MCU. 

Currently implemented interfaces:
- EEPROM with 16-bit addressation.
- I2C/TWI in master mode.
- UART with FIFO.
- SPI in master mode.
- Some text processing and time conversion functions.

Currently implemented devices:
- DS1307/DS3231 (I2C-based RTC)

Plans:
- 1-Wire (interrupt-based).
- Power management or sleep modes.
- RTC (based on async timer with 32.768 crystal).
- Support for MCUs with multiple SPI/UART/I2C interfaces.
