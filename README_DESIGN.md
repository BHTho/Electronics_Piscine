# BOM

| LCSC Part Number | Manufacture Part Number | Manufacturer | Package | Description | Quantity |
|---|---|---|---|---|---|
|C14663|CC0603KRX7R9BB104|YAGEO|0603|50V 100nF X7R ±10% 0603 Ceramic Capacitors RoHS|3|
|C15849|CL10A105KB8NNNC|Samsung Electro-Mechanics|0603|50V 1uF X5R ±10% 0603 Ceramic Capacitors RoHS|1|
|C98220|RC0603FR-0710KL|YAGEO|0603|100mW 10kΩ 75V ±100ppm/℃ Thick Film Resistor ±1% 0603 Chip Resistor - Surface Mount RoHS|2|
|C14877|ATMEGA328P-AU|MICROCHIP|TQFP-32(7x7)|AVR 20MHz 23 TQFP-32(7x7) Microcontrollers RoHS|1|
|C13738|X322516MLB4SI|YXC Crystal Oscillators|SMD3225-4P|Crystal Oscillator 9pF SMD3225-4P Crystals RoHS|1|
|C38523|CL10C120JB8NNNC|Samsung Electro-Mechanics|0603|50V 12pF C0G ±5% 0603 Ceramic Capacitors RoHS|2|
|C916074|TZ-P2-0603YGTCS1-0.6T|TUOZHAN|0603|20mA 50mcd 570nm~575nm Yellow Green 1.9V~2.4V 60mW 0603 LED Indication - Discrete RoHS|1|
|C965799|XL-1608SURC-06|XINGLIGHT|0603|20mA 225mcd op View Mount 620nm~630nm Red 2.3V 50mW 0603 LED Indication - Discrete RoHS|1|
|C231329|B3U-1000P|OMRON|SMD,3x2.5mm|12V 2.5mm Round Button 3mm SPST 50mA SMD,3x2.5mm Tactile Switches RoHS|1|

# Pinout

Pinout for J1 (left-gpio):

| Pin number | Pin name | Pin net |
|------------|----------|---------|
| 1          |          | RAW     |
| 2          |          | GND     |
| 3          |          | DTR     |
| 4          |          | RAW     |
| 5          |          | A3      |
| 6          |          | A2      |
| 7          |          | A1      |
| 8          |          | A0      |
| 9          |          | SCK     |
| 10         |          | MISO    |
| 11         |          | MOSI    |
| 12         |          | D10     |


Pinout for U1 (ATmega328P-A):

| Pin number | Pin name  | Pin net                  |
|------------|-----------|--------------------------|
| 1          | PD3       | D3                       |
| 2          | PD4       | D4                       |
| 3          | GND       | GND                      |
| 4          | VCC       | RAW                      |
| 5          |           |                          |
| 6          |           |                          |
| 7          | XTAL1/PB6 | Net-(U1-XTAL1{slash}PB6) |
| 8          | XTAL2/PB7 | 16MHz                    |
| 9          | PD5       | D5                       |
| 10         | PD6       | D6                       |
| 11         | PD7       | D7                       |
| 12         | PB0       | D8                       |
| 13         | PB1       | D9                       |
| 14         | PB2       | D10                      |
| 15         | PB3       | MOSI                     |
| 16         | PB4       | MISO                     |
| 17         | PB5       | SCK                      |
| 18         | AVCC      | RAW                      |
| 19         | ADC6      | NC                       |
| 20         | AREF      | Net-(U1-AREF)            |
| 21         |           |                          |
| 22         | ADC7      | NC                       |
| 23         | PC0       | A0                       |
| 24         | PC1       | A1                       |
| 25         |           |                          |
| 26         | PC3       | A3                       |
| 27         | PC4       | NC                       |
| 28         | PC5       | NC                       |
| 29         | RESET/PC6 | DTR                      |
| 30         | PD0       | RXI                      |
| 31         | PD1       | TX0                      |
| 32         | PD2       | D2                       |


Pinout for J2 (right-gpio):

| Pin number | Pin name | Pin net |
|------------|----------|---------|
| 1          |          | D9      |
| 2          |          | D8      |
| 3          |          | D7      |
| 4          |          | D6      |
| 5          |          | D5      |
| 6          |          | D4      |
| 7          |          | D3      |
| 8          |          | D2      |
| 9          |          | GND     |
| 10         |          | DTR     |
| 11         |          | RXI     |
| 12         |          | TX0     |

Pinout for J3 (bottom-gpio):

| Pin number | Pin name | Pin net |
|------------|----------|---------|
| 1          |          | DTR     |
| 2          |          | TX0     |
| 3          |          | RXI     |
| 4          |          | RAW     |
| 5          |          | GND     |
| 6          |          | GND     |
