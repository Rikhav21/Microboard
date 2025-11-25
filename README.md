# Microboard
# About
So this is a devboard that I made because I lose wires to upload code to my arduinos all the time, so I just wanted to make a devboard where you can just plug it into the computer, and run suff. So one that that you will probably notice it that I swapped out the USB recepticle for a USB plug, and I also just tried to utilize as much of the IO as possible. Also I think that I never actually saw a squre devboard, so I also tried to make it a unique shape. In the rengers you can not see the USB-C plug, so I will update with pictures when I actually build it. ![img](/imgs/top.png)
![img](/imgs/back.png)
![img](/imgs/pins.png)
![img](/imgs/clear.png)

# Schematic
So hile making the schematic, I think that it looks pretty similar to most other devboards. As I said before, I tried to use all of the pins on the MUCH, so everything is used.
![img](/imgs/Schem.png)

# PCB
This was actually my first time using vias, and having to reroute something so many times. It was also my first time uring pours, but that made it a lot easier. I tried to get most of the routing done on the front, but there are some vias to the back of the PCB.
![img](/imgs/PCB.png)

# Making
So for building this I am ordering the PCB from JLCPCB and all of the other components from LCSC. I am going to hald solder all of the components, but you could do PCBA. The cost should be around $26, but that is counting all of the MOQs, realistically you coulb proabably make 5 of them while spending less than $39 and the majority of the cost is in shipping.

# BOM
| Mfr. | Order Qty. | Unit Price(USD) | Ext. Price(USD) | Package | Description | Product Link |
|------|------------|----------------|----------------|---------|-------------|--------------|
| Samsung Electro-Mechanics | 20 | 0.0101 | 0.20 | 0805 | 10uF 0805 Ceramic Capacitors | [Link](https://www.lcsc.com/product-detail/C15850.html) |
| FH | 100 | 0.0031 | 0.31 | 0603 | 15pF 0603 Ceramic Capacitors | [Link](https://www.lcsc.com/product-detail/C91703.html) |
| Raspberry Pi | 1 | 0.9440 | 0.94 | LQFN-56(7x7) |  | [Link](https://www.lcsc.com/product-detail/C2040.html) |
| Hong Cheng | 5 | 0.0805 | 0.40 | Through Hole, Right Angle, P=2.54mm | Right Angle, P=2.54mm Headers, Male Pins RoHS | [Link](https://www.lcsc.com/product-detail/C41376120.html) |
| YAGEO | 100 | 0.0006 | 0.06 | 0402 | 10kΩ 0402 Resistor | [Link](https://www.lcsc.com/product-detail/C60490.html) |
| YAGEO | 100 | 0.0006 | 0.06 | 0402 | 1kΩ 0402 Resistor | [Link](https://www.lcsc.com/product-detail/C106235.html) |
| Huiyuan crystal | 10 | 0.0603 | 0.60 | SMD3225-4P | Crystal Oscillator 20pF SMD3225-4P | [Link](https://www.lcsc.com/product-detail/C5265859.html) |
| Winbond | 1 | 1.6062 | 1.61 | SOIC-8-208mil | 128Mbit 2.7V~3.6V 133MHz SPI SOIC-8 | [Link](https://www.lcsc.com/product-detail/C97521.html) |
| UNI-ROYAL | 100 | 0.0006 | 0.06 | 0402 | 27Ω 0402 Resistor | [Link](https://www.lcsc.com/product-detail/C25100.html) |
| UNI-ROYAL | 100 | 0.0005 | 0.05 | 0402 | 5.1kΩ 0402 Resistor | [Link](https://www.lcsc.com/product-detail/C25905.html) |
| YAGEO | 100 | 0.0009 | 0.09 | 0402 | 100nF 0402 Ceramic Capacitors | [Link](https://www.lcsc.com/product-detail/C60474.html) |
| ALPSALPINE | 5 | 0.1277 | 0.64 | SMD, 3.9x2.9mm | Round Button 3.9mm SPST | [Link](https://www.lcsc.com/product-detail/C115357.html) |
| Samsung Electro-Mechanics | 100 | 0.0030 | 0.30 | 0402 | 25V 1uF X5R ±10% 0402 Ceramic Capacitors RoHS | [Link](https://www.lcsc.com/product-detail/C52923.html) |
| MICROCHIP | 1 | 0.5422 | 0.54 | SOT-89-3 | Fixed 3.3V SOT-89-3 Voltage Regulator | [Link](https://www.lcsc.com/product-detail/C632000.html) |
| MOLEX | 1 | 1.1995 | 1.20 | SMD | 1 24P -30℃~+85℃ Type-C SMD USB | [Link](https://www.lcsc.com/product-detail/C561769.html) |
|PCB+Shipping  |  |  |$5.12  |  |  |  |
|LCSC shipping + handling total  |   ||$18.59  |  |  |  |
|Total  |  |  |$25.28   |  |  |  |

