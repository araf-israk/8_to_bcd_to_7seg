### 8 Bit Binary to Binary Codded Decimal to 3 Digit 7 segments converter using only transistors.

After watching [Visualizing Data with 7-Segment Displays -  Sebastian Lague](http://www.youtube.com/watch?v=hEDQpqhY2MA "Visualizing Data with 7-Segment Displays -  Sebastian Lague"), I wanted to make a real life version using only transistors. I wanted to see how the logic gate would turn on and off simultaneously. My ultimate goal was to create a 16 bit computer using only transistors so this was the first test of the logic gate designs. I had to hand assemble everything since It was too expensive to use PCB assembly service and I also forgot to order the stencil and had to do everything manually. It was a pain to assemble and solder everything. This design uses 736 npn transistors (sot-23). bottom part consists of 2x 4bit synchronous counter, 555 timer, 2x quad 2 to 1 multiplexer and 10 switches ( 8 for the input, 1 for switching between the counter and the manual input and one for on/off). middle 7 modules are the double dabble circuit that shifts and adds 3 to the input and the top 3 modules are the bcd to 7 segment converters. doing this in simulation vs in real life was very different and a great learning experience for me.

![pic0](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic1.png?raw=true)

![pic1](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/1000038957.jpg?raw=true)

Blue leds indicate the logic gate inputs and the red leds indicate the output.

![pic2](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/1000038930.jpg?raw=true)

![pic3](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic2.png?raw=true)

### Doubble Dabble Modules.
![pic4](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic3.jpg?raw=true)
![pic5](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic4.jpg?raw=true)

### BCD to 7 Segment Converter.
![pic6](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic6.jpg?raw=true)
![pic7](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic5.jpg?raw=true)

### Main Schematics.
![pic8](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic8.jpg?raw=true)
![pic9](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic9.jpg?raw=true)
![pic10](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/pic10.jpg?raw=true)

### Logic Gates.
![pic11](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/AND_GATE_PIC.jpg?raw=true)
![pic12](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/NAND_GATE_PIC.jpg?raw=true)
![pic13](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/NOR_GATE_PIC.jpg?raw=true)
![pic14](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/NOT_GATE_PIC.jpg?raw=true)
![pic15](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/OR_GATE_PIC.jpg?raw=true)
![pic16](https://github.com/araf-israk/8_to_bcd_to_7seg/blob/master/pictures/XOR_GATE_PIC.jpg?raw=true)
