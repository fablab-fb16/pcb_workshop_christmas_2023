# Bauanleitung (DE)

Dies ist eine detaillierte Anleitung mit Bildern. tl;dr -> [Assembly List](/documentation/Assembly%20List.md)

English Version: [Build Instructions](/documentation/Build%20Instructions.md)

## Allgemeine Infos
- Wenn du noch nie gelötet hast, schau dir die Anleitung an (auf Englisch, mit Bildern): [How to solder](/documentation/How%20to%20Solder.md)
- Alle Komponenten werden auf der Seite der Platine plaziert, auf der die zugehörige Markierung des Bauteils ist. Gelötet wird immer auf der anderen Seite der Platine.
- Alle Bauteile haben eine Bezeichnung welche in der Anleitung genannt wird, z.B. "R1" oder "D9". Diese Bezeichnung ist auch auf der Platine aufgedruckt. Dort muss das jeweilige Bauteil platziert werden.
- Manche Komponenten haben eine Orientierung -> Es ist wichtig, dass sie richtigherum eingebaut werden. Dies ist in der Anleitung in rot mit "Caution" gekennzeichnet. Einbaurichtung vor dem Löten nochmal prüfen. 😉
- Have fun. 👩‍🏭👨‍🏭

## Bau die Weihnachtsbaumkugel
### Übersicht
![Overview](/documentation/images/instruction_images/000_overview.jpg)
![Front-Back](/documentation/images/instruction_images/001_front_back.jpg)


### Erstes Bauteil - Diode: D9
![Diode](/documentation/images/instruction_images/010_diode.jpg)

Biege die Beine der Diode (U-förmig)
![Diode Bent](/documentation/images/instruction_images/011_diode_bent.jpg)

Stecke sie auf die Platine an der Position D9 (s. Bild unten).
> [!Caution]
> Beachte die Einbaurichtung: Silberner Ring nach rechts, wie auf der Platine markiert.

![Diode on Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(1).png)

Stecke die Diode bis ganz auf die Platine. Drehe die Platine um und löte die beiden Kontakte.
![Diode Board Flipped](/documentation/images/instruction_images/012_diode_board_flipped.jpg)
![Diode Soldered](/documentation/images/instruction_images/013_diode_soldered.jpg)

Schneide die Beine **oberhalb** der Lötstellen ab (nicht die Lötstelle abschneiden).
![Diode Legs cut](/documentation/images/instruction_images/014_diode_legs_cut.jpg)
![Diode Done](/documentation/images/instruction_images/015_diode_done.jpg)

Fertig mit dem ersten Bauteil.

### Widerstände: R1, R2, R3, R4, R5, R6, R7, R8
![LED Resistors 8x 1.3k](/documentation/images/instruction_images/020_led_resistors.jpg)
Identifiziere die Widerstände an ihren Farbringen: braun - orange - schwarz - braun - braun (Wert: 1.3k)

Biege die Beine (U-förmig), wie bei der Diode.

Stecke sie auf die Platine (diesmal ist die Einbaurichtung egal).
![LED Resistors Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(2).png)

Löten, Beine abschneiden, wiederholen bis alle Widerstände aufgelötet sind.

![LED Resistors Done](/documentation/images/instruction_images/021_led_resistors_done.jpg)


### Widerstände: R9, R10
![Resistors 2x 10k](/documentation/images/instruction_images/030_resistors_10k.jpg)
Identifiziere die Widerstände an ihren Farbringen: braun - schwarz - schwarz - rot - braun (Wert: 10k)

Beine biegen, auf Platine stecken, löten, Beine abschneiden, wiederholen.
![Resistors Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(3).png)
![Resistors 2x 10k done](/documentation/images/instruction_images/031_resistors_10k_done.jpg)

### Timer: U1, U3
![Timers Detail](/documentation/images/instruction_images/040_timer_detail.jpg)
> [!Caution]
> Beachte die Einbaurichtung! Kleine Einkerbung nach oben.

![Timers Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(4).png)
![Timers done](/documentation/images/instruction_images/041_timer_done.jpg)

### Schieberegister: U2
![Shift register Detail](/documentation/images/instruction_images/050_shift_register_detail.jpg)
> [!Caution]
> Beachte die Einbaurichtung! Kleine Einkerbung nach oben.

![Shift register Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(5).png)
![Shift register done](/documentation/images/instruction_images/051_shift_register_done.jpg)

### Kondensatoren: C1, C4, C5, C6, C7
![Capacitors 100nF Detail](/documentation/images/instruction_images/060_capacitor_100n_detail.jpg)

> [!Caution]
> Achtung, es gibt Verschiedene! Hier brauchst du die Kleineren mit dem Aufdruck "104" (Wert: 100nF).

![Capacitors 100nF Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(6).png)
![Capacitors 100nF done](/documentation/images/instruction_images/061_capacitor_100n_done.jpg)


### Kondensatoren: C2, C3
![Capacitors 4.7uF Detail](/documentation/images/instruction_images/070_capacitor_475K_detail.jpg)

> [!Caution]
> Achtung, es gibt Verschiedene! Hier brauchst du die Größeren mit dem Aufdruck "475K" (Wert: 4.7uF).

![Capacitors 4.7uF Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(7).png)
![Capacitors 4.7uF done](/documentation/images/instruction_images/071_capacitor_475K_done.jpg)

### LEDs: D1, D2, D3, D4, D5, D6, D7, D8
![LEDs Detail](/documentation/images/instruction_images/080_leds_detail.jpg)
Mische die verschiedenen Farben, wie du magst.
> [!Caution]
> Beachte die Einbaurichtung! Kurzes Bein in das Loch mit dem quadratischen Lötpad (s. Bild).

![LEDs Detail](/documentation/images/instruction_images/081_leds_orientation.jpg)
![LEDs Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(9).png)
![LEDs Done](/documentation/images/instruction_images/082_leds_done.jpg)

### Jumper: JP1, JP2, JP3, ON/OFF
![Jumpers Detail](/documentation/images/instruction_images/090_jumpers_detail.jpg)
Schneide sie mit dem Seitenschneider in 4 Stücke á 3 Pins (s. Bild).

![Jumpers Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(8).png)
![Jumpers Done](/documentation/images/instruction_images/091_jumpers_done.jpg)


### Potentiometer: RV1, RV2
![Potentiometers Detail](/documentation/images/instruction_images/100_poti_detail.jpg)
Die Potentiometer "klipsen" auf die Platine - das braucht etwas Kraft. Löte dann alle Kontakte, auch die großen.

![Potentiometers Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.F(10).png)
![Potentiometers Done](/documentation/images/instruction_images/101_poti_done.jpg)

### Batterie-Anschluss: Battery_9V
![Battery Connector Detail](/documentation/images/instruction_images/110_battery_connector_detail.jpg)
> [!Caution]
> Dieses Teil gehört auf der Rückseite der Platine und wird auf der Vorderseite gelötet.
> Beachte die Einbaurichtung: Rotes Kabel an **+** , Schwarzes Kabel an **-**

![Battery Connector Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.B.png)
![Battery Connector Done](/documentation/images/instruction_images/111_battery_connector_done.jpg)


### Kabel Buchsen: J1, J2
![Wire Connectors Detail](/documentation/images/instruction_images/120_wire_connector_detail.jpg)
> [!Caution]
> Dieses Teil gehört auf der Rückseite der Platine und wird auf der Vorderseite gelötet.
> Beachte die Einbaurichtung! Siehe Bilder.

![Wire Connectors Board Drawing](/documentation/images/board_drawing_with_marked_components/christmas.B(1).png)
![Wire Connectors Done](/documentation/images/instruction_images/121_wire_connector_done.jpg)

**Glückwunsch, du hast das Löten geschafft. Es sind nur noch wenige Schritte nötig, bis du fertig bist.**

### Stecke die Jumper auf
![Jumper Connectors Detail](/documentation/images/instruction_images/130_jumpers_detail.jpg)
Stecke die vier Jumper wie folgt auf (ebenfalls im unteren Bild zu sehen)
- JP1, JP2, JP3: obere Position
- OFF/ON: linke Position (OFF)

![Jumper Connectors Done](/documentation/images/instruction_images/131_jumpers_done.jpg)

### Befestige die Batterie und schließe sie an
Wickele die Batterie in Isolierband / Klebeband (damit sie keinen Kurschluss auf der Platine verursacht).
![Battery Detail](/documentation/images/instruction_images/140_battery_detail.jpg)

Nutze ein Gummiband um die Batterie auf der Rückseite der Platine zu befestigen (s. Bilder).
Schließe die Batterie an das Kabel an (Richtung beachten).

![Battery Done](/documentation/images/instruction_images/141_battery_done.jpg)


### Knote einen Faden zum Aufhängen an (optional)
![String Done](/documentation/images/instruction_images/150_string.jpg)

### Geschafft! Stecke den Jumper "OFF/ON" in die rechte Position (ON) und los geht's. ✨
Wenn du alles richtig gemacht hast, beginnen die LEDs zu blinken.
Mit den zwei Potentiometern kannst du das Muster und die Geschwindigkeit des Blinkens verstellen.

Für mehr Infos zu Benutzung, siehe [Usage Instructions](/documentation/Usage%20Instructions.md) (auf Englisch).


![Finally Done](/documentation/images/instruction_images/999_final.gif)

