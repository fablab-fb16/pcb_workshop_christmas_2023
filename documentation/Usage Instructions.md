# Usage Instructions
The Christmas Ball has two Potentiometers and four Jumpers for control.

![](/documentation/images/front_small_low_res.png)

## Stand-Alone use
- JP1, JP2, JP3: upper position
- OFF/ON: right position
- use both potentiometers to control blinking pattern and speed; just play around

## Details for daisy-chaining
Connect multiple christmas balls via the connectors on the back and set the jumpers as you want - description below:
### Jumpers
| Name   | Description                 | Upper Position                  | Lower Position                 |
| ------ | --------------------------- | ---------------------------------------------------- | -------------------------------------------------- |
| JP1    | Shift Register Data Source  | use on-board timer signal                            | use signal from INPUT connector                    |
| JP2    | Shift Register Clock Source | use on-board timer signal                            | use signal from INPUT connector                    |
| JP3    | Data Output                 | Series Connection: send shift register output to OUT | Parallel Connection: send data timer output to OUT |
| OFF/ON | Turn power on/off           | -                                                    | -                                                  |

### Potentiometers

- Left (RV1): Control Data Timer signal frequency
- Right (RV2): Control Clock Timer signal frequency (RV1)
