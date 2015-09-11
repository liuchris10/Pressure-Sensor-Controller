Pressure Sensor Pin Outs

Arduino Pins
0 ------> Comm Tx (R1OUT MAX3232)
1 ------> Comm Rx (T1IN MAX3232)
2 ------> Pressure Pin Control
3 ------> Interrupt Pin - JUMP TO PIN 0
4 ------> 
5 ------> SD Card CS
6 ------> Modem Tx (Tx-RS232 Conv)
7 ------> Modem Rx (Rx-RS232 Conv)
8 ------> Pressure Tx (R2OUT MAX3232)
9 ------> Pressure Rx (T2IN MAX3232)
10------> RTC SS
11------> MOSI
12------> MISO
13------> CLK

Modem DB9 Breakout
2 -----> T1OUT MAX3232
3 -----> R1IN MAX3232
5 -----> GND

Pressure Sensor
Rx ----> T2OUT MAX3232
Tx ----> R2IN MAX3232

MAX3232 Breakout
T1OUT -------> Comm Rx (Pin 2)
T2OUT -------> Pressure Rx (Yellow Wire)
R1IN --------> Comm Tx (Pin 3)
R2IN --------> Pressure Tx (Green Wire)
3V-5.5V -----> Power from Arduino
T1IN --------> Pin 1 Arduino
T2IN --------> Pin 9 Arduino
R1OUT--------> Pin 0 Arduino
R2OUT--------> Pin 8 Arduino
