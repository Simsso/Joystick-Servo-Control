# Wireless wiring

## Transmitter Arduino

It's necessary to put all pins to ground which are defined but not used. E.g. if "Taste 7" isn't connected to the joystick it needs to be grounded.

| Pin | Description |
|---|---|
|2|Taste 1|
|4|Taste 2|
|7|Taste 3|
|8|Taste 4|
|13|Taste 7|
|A0|Drehgeber 1|
|A1|Drehgeber 2|
|A2|Drehgeber 3|
|12|Transmitter module data pin|

## Receiver Arduino

| Pin | Description | Servo Control Arduino (pin) |
|---|---|---|
|~~9~~|~~Data link enable pin~~|~~13~~|
|10|Software serial RX|11|
|11|Software serial TX|10|
|12|Receiver module data pin|-|
|GND|Ground|GND|

## Servo Control Arduino

| Pin | Description | Receiver Arduino (pin) |
|---|---|---|
|9|Servo 1 pin|-|
|10|Software serial RX|11|
|11|Software serial TX|10|
|~~13~~|~~Data link enable pin~~|~~9~~|
|GND|Ground|GND|
