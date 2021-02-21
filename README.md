==============================
Electronics design Task#4
==============================
Concept and Design of a LoRa controlled 2-pair brushed DC motor setup.

Robot will be of same specs as this:
https://www.superdroidrobots.com/shop/item.aspx/configurable-ig52-sb4-t-custom-size-4wd-all-terrain-robot/2809/
But with custom electronics.

Choice of motor - WITH ENCODERS (total 4 motors):
https://www.superdroidrobots.com/shop/item.aspx/ig52-04-24vdc-044-rpm-gear-motor-with-encoder/1705/
OR
https://www.superdroidrobots.com/shop/item.aspx/ig42-24vdc-047-rpm-gear-motor-with-encoder/2637/

Battery:
2x12V=24V

Design Goals:
The final product will be
Unit #1) A LoRa receiver+microcontroller controller unit to drive the two DC motors.
Unit #2) A LoRa remote to send FORWARD, REVERSE, LEFT, RIGHT, BRAKE signals to the receiver.
The DC motors have encoders, so readings must be through via interrupts.
Power supply will be 24V battery (two 12V in series)
ESP32-WROOM-32E can be used
Apart from LoRa, the microcontroller unit must also CAN enabled, so that it can accept instructions of what was developed under Task#3
LoRa communication must be secured.

Expectations of the task:
=========================
Design Research
All programming
Wiring diagram (not professional, rough on paper/MS PAINT will do)
Enclosure design.
Input / Output connection terminal selection.
PCB design of mating board (if any)
Wiring and assembly instruction documentation.
Bill of Material documentation.
