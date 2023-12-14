# Build Instructions (EN)

This is a detailed guide with images. tl;dr -> [Assembly List](/documentation/Assembly%20List.md)

## General Info
- If you don't know how to solder, look at [How to solder](/documentation/How%20to%20Solder.md)
- All components are placed on the side of the board, where their marking is. Soldering is done on the opposite side.
- All components have a label e.g. "R1" or "D9" which tells you, where to put the component on the board.
- Some components are directional -> Orientation matters for them. This is denoted with a red "Caution" tag, because it's important. Double-check orientation **before** soldering.
- If you are not sure about something: Ask before soldering 😉
- Have fun. 👩‍🏭👨‍🏭

## Build the Christmas Tree Ball
### Overview
![Overview](/documentation/images/instruction_images/000_overview.jpg)
![Front-Back](/documentation/images/instruction_images/001_front_back.jpg)


### First Component - Diode: D9
![Diode](/documentation/images/instruction_images/010_diode.jpg)

Bend the legs of the Diode (U-shape)
![Diode Bent](/documentation/images/instruction_images/011_diode_bent.jpg)

Place it on the board at position D9. Push it all the way down.
> [!Caution]
> For this part the orientation is important! Silver ring to the right.

![Diode on Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(1).png)

Flip the board and solder the two connections.
![Diode Board Flipped](/documentation/images/instruction_images/012_diode_board_flipped.jpg)
![Diode Soldered](/documentation/images/instruction_images/013_diode_soldered.jpg)

Cut the excess component legs above the solder joint.
![Diode Legs cut](/documentation/images/instruction_images/014_diode_legs_cut.jpg)
![Diode Done](/documentation/images/instruction_images/015_diode_done.jpg)

### Resistors: R1, R2, R3, R4, R5, R6, R7, R8
![LED Resistors 8x 1.3k](/documentation/images/instruction_images/020_led_resistors.jpg)
Identify them by Color Code: brown - orange - black - brown - brown (Value: 1.3k)

Bend the legs (U-shape)

Place on board (orientation doesn't matter).
![LED Resistors Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(2).png)

Solder, cut legs, repeat.
![LED Resistors Done](/documentation/images/instruction_images/021_led_resistors_done.jpg)


### Resistors: R9, R10
![Resistors 2x 10k](/documentation/images/instruction_images/030_resistors_10k.jpg)
Identify them by Color Code: brown - black - black - red - brown (Value: 10k)

Bend legs, place on board, solder, cut legs, repeat.
![Resistors Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(3).png)
![Resistors 2x 10k done](/documentation/images/instruction_images/031_resistors_10k_done.jpg)

### Timers: U1, U3
![Timers Detail](/documentation/images/instruction_images/040_timer_detail.jpg)
> [!Caution]
> Orientation is important! Little notch to the top.

![Timers Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(4).png)
![Timers done](/documentation/images/instruction_images/041_timer_done.jpg)

### Shift register: U2
![Shift register Detail](/documentation/images/instruction_images/050_shift_register_detail.jpg)
> [!Caution]
> Orientation is important! Little notch to the top.

![Shift register Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(5).png)
![Shift register done](/documentation/images/instruction_images/051_shift_register_done.JPG)

### Capacitors: C1, C4, C5, C6, C7
![Capacitors 100nF Detail](/documentation/images/instruction_images/060_capacitor_100n_detail.jpg)
Identify them: They are the smaller ones with "104" printed on.  (Value: 100nF)

![Capacitors 100nF Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(6).png)
![Capacitors 100nF done](/documentation/images/instruction_images/061_capacitor_100n_done.jpg)


### Capacitors: C2, C3
![Capacitors 4.7uF Detail](/documentation/images/instruction_images/070_capacitor_475K_detail.jpg)
Identify them: They are the larger ones with "475K" printed on. (Value: 4.7uF)

![Capacitors 4.7uF Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(7).png)
![Capacitors 4.7uF done](/documentation/images/instruction_images/071_capacitor_475K_done.jpg)

### LEDs: D1, D2, D3, D4, D5, D6, D7, D8
![LEDs Detail](/documentation/images/instruction_images/080_leds_detail.jpg)
Mix colors as you want.
> [!Caution]
> Orientation is important! Shorter leg into the hole with the squared pad. (see image)

![LEDs Detail](/documentation/images/instruction_images/081_leds_orientation.jpg)
![LEDs Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(9).png)
![LEDs Done](/documentation/images/instruction_images/082_leds_done.jpg)

### Jumpers: JP1, JP2, JP3, ON/OFF
![Jumpers Detail](/documentation/images/instruction_images/090_jumpers_detail.jpg)
Cut them with the cutter to 4 pieces á 3 Pins (see image).

![Jumpers Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(8).png)
![Jumpers Done](/documentation/images/instruction_images/091_jumpers_done.jpg)


### Potentiometers: RV1, RV2
![Potentiometers Detail](/documentation/images/instruction_images/100_poti_detail.jpg)
They snap to the board; use gentle force to put them on. Solder all contacts, the large ones too.

![Potentiometers Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(10).png)
![Potentiometers Done](/documentation/images/instruction_images/101_poti_done.jpg)

### Battery Connector: Battery_9V
![Battery Connector Detail](/documentation/images/instruction_images/110_battery_connector_detail.jpg)
> [!Caution]
> This is placed on the back side and soldered on the front side.
> Orientation is important: Red wire to **+** , black wire to **-**

![Battery Connector Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.B.png)
![Battery Connector Done](/documentation/images/instruction_images/111_battery_connector_done.jpg)


### Wire Connectors: J1, J2
![Wire Connectors Detail](/documentation/images/instruction_images/120_wire_connector_detail.jpg)
> [!Caution]
> This is placed on the back side and soldered on the front side.
> Orientation is important! See images.

![Wire Connectors Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.B(1).png)
![Wire Connectors Done](/documentation/images/instruction_images/121_wire_connector_done.jpg)

**Congratulations, you're done with soldering. Only a few steps are left.**

### Place Jumpers
![Jumper Connectors Detail](/documentation/images/instruction_images/130_jumpers_detail.jpg)
Place the four Jumper connectors (also shown in the below image)
- JP1, JP2, JP3: on the top position
- OFF/ON: on the left position (OFF)

![Jumper Connectors Done](/documentation/images/instruction_images/131_jumpers_done.jpg)

### Mount and connect battery
Wrap the battery in tape (for insulation)
![Battery Detail](/documentation/images/instruction_images/140_battery_detail.jpg)

Use the rubber band to attach the battery to the back of the board (see images).
Connect the battery to the battery connector.

![Battery Done](/documentation/images/instruction_images/141_battery_done.jpg)


### Attach string (optional)
![String Done](/documentation/images/instruction_images/150_string.jpg)

### You're done! Plug the Jumper "OFF/ON" to the right position (ON) and enjoy. ✨
Turn the two potentiometers to adjust the blinking pattern and speed.

For more information check the [Usage Instructions](/documentation/Usage%20Instructions.md).


![Finally Done](/documentation/images/instruction_images/999_final.gif)

