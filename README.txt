
Digital LED thermometer on ATTINY13 and TM1637 4-digit LED Arduino module. 
Uses analog temperature sensor TMP36 (for -50C - 100C degrees) or LM35 (for 0-100C degrees measurement)

How to connect

LM35 Vout to ATTINY13 PB4 pin
TM1637 DIO_PIN to ATTINY13 PB0 pin
TM1637 CLK_PIN to ATTINY13 PB1 pin

VCC (5V from USB or LM7805 stabilizer) and GND must be connected to both ATTINY13 and TM1637 module

5V from VCC is used as a reference for LM35/TM1637 measurement.

 

