# PCB assembly instructions

## Ordering PCBs

Get Gerber files and send to fab house

## Assembly

<img src="img/PCB_1.png" alt="" width="600"/><br>
PCB isometric view

<img src="img/PCB_2.png" alt="" width="600"/><br>
PCB Top view

<img src="img/PCB_3.png" alt="" width="600"/><br>
PCB Side view

<img src="img/PCB_4.png" alt="" width="600"/><br>
PCB Side view

Tensy with headers | Teensy on PCB
---|---
<img src="img/PCB_5.png" alt="" width="400"/> |<img src="img/PCB_6.png" alt="" width="400"/>

Schematics | Component| Value
-----------|----------|---|
IC1 - IC5, IC7|Gate driver|SN75451BP
IC6|Voltage regulator|LM340
R1 - R8|Resistor| 65 Ω
R11 - R18|Resistor|330 Ω between pin 1 & 2
R21|Resistor| 5 kΩ
C1 - C8|Capacitor|0.1 µF
C11,C12|Capacitor|10 µF
TX1 - TX8|Fiber optic transmitter|SP000063814
RX1 - RX8|Fiber optic receiver|SP000063855
Teensy 3.5 | Use version 3.5 **NOT 3.6**
