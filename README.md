# ArduinoUnoR3

This is a DIY Arduino(TM) UNO R3 board designed using KiCad

- **A Detailed walk through of how I made this porject is explained below**

## Walk through of the project

- The first micro controller the ATMEGA16U2-A serves as the USB to UART converte.
- Data comes into the USB.
- Programming through the IDE one uses a USB interface, however, one cannot use one when developing your own board at first through the first time. Since it is a USB boot loade, so it doesn't know how to load firmware through its embedded firmwar, we should program it to tell it how to do it.
- Power comes in through the USB port(5V),  
