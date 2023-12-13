# Build Instructions (EN)

This is a detailed guide with images. tl;dr -> [Assembly List](/documentation/Assembly%20List.md)

## General Info
- If you don't know how to solder, look at [How to solder](/documentation/How%20to%20Solder.md)
- All components are placed on the side of the board, where their marking is. Soldering is done on the opposite side.
- Some components are directional -> Orientation matters. This is denoted with a "Caution" tag, cause it's important. Double-check orientation **before** soldering.
- If you are not sure about something: Ask before soldering 😉
- Have fun. 👩‍🏭👨‍🏭

## Build the Christmas Tree Ball
### Overview
- <span style="color:green">Image: component overview</span>
- <span style="color:green">Image: PCB front side, Back side</span>

### First Component - Diode: D9
- <span style="color:green">Image: Diode detail image</span>
- Bend the legs of the Diode (U-shape)
- Place it on the board at position D9.
> [!Caution]
> For this part the orientation is important! Silver ring to the right.
- <span style="color:green">Image: Diode placed on board</span>
- Flip the board.
- Solder the two connections.
- <span style="color:green">Image: soldered</span>
- Cut the excess component legs above the solder joint.
- <span style="color:green">Image: legs cut</span>

### Resistors: R1, R2, R3, R4, R5, R6, R7, R8
- <span style="color:green">Image: resistor detail image 8x</span>
- Identify them by Color Code: brown - orange - black - brown - brown (Value: 1.3k)
- Bend the legs (U-shape)
- Place on board (orientation doesn't matter).
- <span style="color:green">Image: resistors placed</span>
- Solder, cut legs, repeat.

### Resistors: R9, R10
- <span style="color:green">Image: resistor detail image 2x</span>
- Identify them by Color Code: brown - black - black - red - brown (Value: 10k)
- bend legs, place on board, solder, cut legs, repeat.
- <span style="color:green">Image: resistors placed</span>

### Timers: U1, U3
- <span style="color:green">Image: timers detail image</span>
> [!Caution]
> Orientation is important! Little notch to the top.
- <span style="color:green">Image: timers placed</span>

### Shift register: U2
- <span style="color:green">Image: shift register detail image</span>
> [!Caution]
> Orientation is important! Little notch to the top.
- <span style="color:green">Image: shift register placed</span>

### Capacitors: C1, C4, C5, C6, C7
- <span style="color:green">Image: Capacitors detail image</span>
- Identify: They are the smaller ones with "104" printed on.  (Value: 100nF)
- <span style="color:green">Image: Capacitors placed</span>

### Capacitors: C2, C3
- <span style="color:green">Image: Capacitors detail image</span>
- Identify: They are the larger ones with "475K" printed on. (Value: 4.7uF)
- <span style="color:green">Image: Capacitors placed</span>

### LEDs: D1, D2, D3, D4, D5, D6, D7, D8
- <span style="color:green">Image: LEDs detail image</span>
- Mix colors as you want.
> [!Caution]
> Orientation is important! Shorter leg into the hole with the squared pad. (see image)
- <span style="color:green">Image: LEDs placement detail image</span>
- <span style="color:green">Image: LEDs placed</span>

### Capacitors: C2, C3
- <span style="color:green">Image: Capacitors detail image</span>
- Identify: They are the larger ones with "475K" printed on them. (Value: 4.7uF)
- <span style="color:green">Image: Capacitors placed</span>

### Jumpers: JP1, JP2, JP3, ON/OFF
- <span style="color:green">Image: Jumpers detail image</span>
- Cut them with the cutter to 3 Pins.
- <span style="color:green">Image: Jumpers placed</span>

### Potentiometers: RV1, RV2
- <span style="color:green">Image: Potentiometers detail image</span>
- They snap to the board; use gentle force to put them on.
- <span style="color:green">Image: Potentiometers placed</span>

### Battery Connector: Battery_9V
- <span style="color:green">Image: Battery Connector detail image</span>
> [!Caution]
> This is placed on the back side and soldered on the front side.
> Orientation is important: Red wire to **+** , black wire to **-**
- <span style="color:green">Image: Battery Connector placed</span>

### Wire Connectors: J1, J2
- <span style="color:green">Image: Wire Connectors detail image</span>
> [!Caution]
> This is placed on the back side and soldered on the front side.
> Orientation is important! See images.
- <span style="color:green">Image: Wire Connectors placed</span>

**Congratulations, you're done with soldering. Only a few steps are left.**

### Place Jumpers
- Place the Jumper connectors as shown in the image
  - JP1, JP2, JP3 on the top position
  - OFF/ON: on the left position (OFF)
- <span style="color:green">Image: Jumper connectors placed</span>

### Attach and connect battery
- wrap the battery in tape (for insulation)
- use the rubber band to attach the battery to the back of the board (see image)
- connect the battery to the battery connector
- <span style="color:green">Image: battery attached and connected</span>

### Attach string (optional)
- <span style="color:green">Image: string connected</span>

### You're done! Plug the Jumper "OFF/ON" to the right position and enjoy. ✨
Turn the two potentiometers to adjust the blinking pattern and speed.

For more information check the [Usage Instructions](/documentation/Usage%20Instructions.md).

- <span style="color:green">GIF: blinking christmas ball</span>

