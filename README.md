temps_utile-
============

teensy 3.1 trigger generator w/ 128x64 oled display.


i/o:

**1 clock input; 1 reset input**

**4 CV inputs (bipolar, assignable to any parameter)**

**6 clock outputs (5 digital, 1 DAC (12 bit))**

**5 modes, selectable per channel (params / channel):** 

- clock division (pulse-width, divisor, inverted)

- LFSR (pulse-width, length, tap1, tap2)

- random (pulse-width, N, inverted)

- euclidian (pulse-width, N (length), K (fill), offset)

- logic (pulse-width, mode (AND, OR, XOR, NAND, NOR), op1, op2)

- (DAC mode; channel #4 only: random, 'binary sequencer' (+/- 5 volts))

25 mm Depth


![My image](https://farm4.staticflickr.com/3948/15552392087_8fb300d861_z.jpg)


