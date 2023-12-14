# Assembly List

Assemble in the listed order for the best experience.

Place components on the side of the PCB where the respective marking is, and solder on the opposite side.

| Reference on PCB               | Component                       | Quantity | Notes                                               |
| ------------------------------ | ------------------------------- | -------- | --------------------------------------------------- |
| D9                             | Diode (1N5817)                  | 1        | Orientation important! Silver ring to the right.    |
| R1, R2, R3, R4, R5, R6, R7, R8 | Resistor (1.3k)                 | 8        | Color Code: brown - orange - black - brown - brown  |
| R9, R10                        | Resistor (10k)                  | 2        | Color Code: brown - black - black - red - brown     |
| U1, U3                         | Timer (NE555P, DIP-8)           | 2        | Orientation important! Notch to the top.            |
| U2                             | Shift Register (4015, DIP-16)   | 1        | Orientation important! Notch to the top.            |
| C1, C4, C5, C6, C7             | Capacitor (100nF, smaller ones) | 5        |                                                     |
| C2, C3                         | Capacitor (4.7uF, larger ones)  | 2        |                                                     |
| JP1, JP2, JP3, ON/OFF          | Jumpers (3 Pins, 2.54mm)        | 4        |                                                     |
| D1, D2, D3, D4, D5, D6, D7, D8 | LEDs                            | 8        | Orientation important! Short leg to square pad.     |
| RV1, RV2                       | Potentiometers                  | 2        |                                                     |
| Battery_9V                     | Battery Cable (9V Block)        | 1        | Place on back side. Red wire to + ; Black wire to - |
| J1, J2                         | Cable Connector                 | 2        | Place on back side.                                 |

After soldering all components, see [last steps in build instructions](/documentation/Build%20Instructions.md#place-jumpers) (from "Place Jumpers" onwards).
