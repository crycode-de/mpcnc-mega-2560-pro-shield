# MPCNC Mega 2560 Pro Shield Changelog

## v1.2 Rev.4 - 2023-12-01

💥 Pins 3 and 4 of IC were swapped which lead to non functional "Spindle VFD Speed Control" part.

Thanks to [Gerssi](https://github.com/Gerssi) for reporting!

To fix this issue in already existing PCBs you may cut the two wires going to IC5 pin 2 and 3 on the PCB and use a small external wire to connect them accordingly.

**Fixed** in revision 4:
![rev4](./doc/changes/IC5A_1.2-rev4_circuit.png)
![rev4](./doc/changes/IC5A_1.2-rev4_layout.png)

**Wrong** in revision 3:
![rev3](./doc/changes/IC5A_1.2-rev3_circuit.png)
![rev3](./doc/changes/IC5A_1.2-rev3_layout.png)
