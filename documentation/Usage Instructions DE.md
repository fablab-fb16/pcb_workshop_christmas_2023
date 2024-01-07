# Gebrauchsanweisung
Dieses Dokument beschreibt die Verwendung der Weihnachtskugel.

Die Weihnachtskugel wird von einer 9-V-Batterie betrieben, die mit einem Gummiband an der Rückseite der Weihnachtskugel befestigt werden kann (Achten Sie darauf, die metallische Außenhülle der Batterie mit Klebeband oder ähnlichem zu isolieren, da die Weihnachtskugel sonst einen Kurzschluss verursacht). Wenn Sie die Weihnachtskugel im Daisy-Chain-Modus verwenden, kann die Batterie jeder Weihnachtskugel in der Kette zur Stromversorgung der gesamten Kette verwendet werden. Achten Sie darauf, alle Weihnachtskugeln mit Batterien auszuschalten, um die gesamte Kette auszuschalten.

Die Weihnachtskugel wird über zwei Potentiometer und vier Jumper gesteuert (Einzelheiten finden Sie im Abschnitt [Steuerungen](#steuerelemente)). Leider waren die im Bausatz enthaltenen Potentiometer nicht die richtigen (sie haben eine lineare statt einer logarithmischen Kennlinie), sodass die Weihnachtskugel nicht so einfach zu bedienen ist, wie sie sein sollte.

Um die Weihnachtskugel einzuschalten, stecken Sie den Jumper mit der Aufschrift „OFF/ON“ in die richtige Position („ON“). Es kann in zwei Modi verwendet werden: [Stand-Alone](#stand-alone-nutzung) und [Daisy-Chained](#daisy-chained-nutzung).

## Steuerelemente
Die Steuerung der Weihnachtskugel erfolgt über zwei Potentiometer und vier Jumper:
![](/documentation/images/front_small_low_res.png)

### Jumper
| Name    | Beschreibung                     | Obere/linke Position                           | Untere/rechte Position                           |
| ------- | -------------------------------- | ---------------------------------------------- | ------------------------------------------------ |
| JP1     | Datenquelle des Schieberegisters | Integriertes Timersignal verwenden             | Verwenden Sie das Signal vom INPUT-Anschluss     |
| JP2     | Taktquelle des Schieberegisters  | Integriertes Timersignal verwenden             | Verwenden Sie das Signal vom INPUT-Anschluss     |
| JP3     | Datenausgabe                     | Reihenschaltung: Schieberegisterausgang an OUT | Parallele Verbindung: Daten-Timer-Ausgabe an OUT |
| AUS/EIN | Strom ein-/ausschalten           | Schalten Sie die Batterie aus                  | Schalten Sie die Batterie ein                    |

### Potentiometer
Aufgrund eines Fehlers im Bestellvorgang waren die im Kit enthaltenen Potentiometer nicht die richtigen (sie haben eine lineare statt einer logarithmischen Kennlinie), daher sind die Potentiometer sehr empfindlich und es kann schwierig sein, die richtige Einstellung zu finden.

| Name | Beschreibung  | Funktion                                                                              |
| ---- | ------------- | ------------------------------------------------------------------------------------- |
| RV1  | Daten-Timer   | Steuerdaten-Timer-Signalfrequenz, die das Blinkmuster steuert                         |
| RV2  | Zeitschaltuhr | Steuern Sie die Signalfrequenz des Clock-Timers, die die Blinkgeschwindigkeit steuert |


## Modi
### Stand-Alone-Nutzung
Die Weihnachtskugel kann im Standalone-Modus verwendet werden, das heißt, sie ist nicht mit einer anderen Weihnachtskugel verbunden.
Um es im Standalone-Modus zu verwenden, stellen Sie die Jumper JP1, JP2 und JP3 auf die obere Position.
Mit dem ON/OFF-Jumper schalten Sie die Weihnachtskugel ein und aus.
Verwenden Sie beide Potentiometer, um das Blinkmuster und die Geschwindigkeit zu steuern. Probieren Sie einfach etwas aus (Einzelheiten finden Sie im Abschnitt [Bedienelemente – Potentiometer](#potentiometer)).

### Daisy-Chained-Nutzung
Verbinden Sie mehrere Weihnachtskugeln über die Anschlüsse auf der Rückseite (Achtung: Verbinden Sie nur die Anschlüsse mit der Beschriftung „INPUT“ mit den Anschlüssen mit der Beschriftung „OUTPUT“, da sonst die Weihnachtskugeln beschädigt werden.)
Stellen Sie die Jumper gemäß der Tabelle im Abschnitt [Bedienelemente – Jumper](#jumper) wie gewünscht ein.
Mit dem ON/OFF-Jumper schalten Sie die Weihnachtskugel ein und aus. Eine Weihnachtskugel in der Kette sollte ausreichen, um die gesamte Kette mit Strom zu versorgen. Wenn Sie viele Weihnachtskugeln verbinden, müssen Sie möglicherweise mehrere Batterien verwenden. Stellen Sie in diesem Fall sicher, dass Sie alle Weihnachtskugeln mit Batterien ausschalten, um die gesamte Kette auszuschalten und umgekehrt.
Wie im Standalone-Modus können Sie die Potentiometer verwenden, um das Blinkmuster und die Geschwindigkeit zu steuern. Probieren Sie einfach etwas aus (Einzelheiten finden Sie im Abschnitt [Bedienelemente – Potentiometer](#potentiometer)).