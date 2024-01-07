# Usage Instructions
This document describes how to use the christmas ball. 

The christmas ball is powered by a 9V battery, which can be fastend to the back of the christmas ball with a rubber band (Make sure to insulate the metalic outer shell of the battery with tape or similar, otherwise the christmas ball will short-circuit). When using the christmas ball in daisy-chained mode, the battery of the any christmas ball in the chain can be used to power the whole chain. Make sure to turn all christmas balls with batteries off, to turn the whole chain off.

The christmas ball is controlled by two potentiometers and four jumpers (see [Controls](#controls) section for details). Unfortunatly, the potentiometers included in the kit were not the correct ones (they have a linear characteristic instead of a logarithmic one), so the christmas ball is not as easy to use as it should be.

To turn the christmas ball on, set the jumper labeled "OFF/ON" to the right position ("ON"). It can be used in two modes: [Stand-Alone](#stand-alone-use) and [Daisy-Chained](#daisy-chained-use). 

## Controls
The christmas ball is controlled by two potentiometers and four jumpers:
![](/documentation/images/front_small_low_res.png)

### Jumpers
| Name   | Description                 | Upper/Left Position                                  | Lower/Right Position                               |
| ------ | --------------------------- | ---------------------------------------------------- | -------------------------------------------------- |
| JP1    | Shift Register Data Source  | Use on-board timer signal                            | Use signal from INPUT connector                    |
| JP2    | Shift Register Clock Source | Use on-board timer signal                            | Use signal from INPUT connector                    |
| JP3    | Data Output                 | Series Connection: send shift register output to OUT | Parallel Connection: send data timer output to OUT |
| OFF/ON | Turn power on/off           | Turn the battery off                                 | Turn the battery on                                |

### Potentiometers
Due to a mistake in the ordering process, the potentiometers included in the kit were not the correct ones (they have a linear characteristic instead of a logarithmic one), so the potentiometers are very sensitive and it can be difficult to find the correct setting.

| Name | Description | Function                                                                 |
| ---- | ----------- | ------------------------------------------------------------------------ |
| RV1  | Data Timer  | Control Data Timer signal frequency, which controls the blinking pattern |
| RV2  | Clock Timer | Control Clock Timer signal frequency, which controls the blinking speed  |


## Modes
### Stand-Alone use
The christmas ball can be used in stand-alone mode, which means that it is not connected to any other christmas ball.  
To use it in stand-alone mode, set the JP1, JP2 and JP3 jumpers to the upper position.  
Use the ON/OFF Jumper to turn the christmas ball off and on.  
Use both potentiometers to control blinking pattern and speed, just play around (see [Controls - Potentiometers](#potentiometers) section for details).

### Daisy-Chained use
Connect multiple christmas balls via the connectors on the back (Attention: only connect the connectors labeled "INPUT" with the connectors labeled "OUTPUT", doing otherwise will damage the christmas balls).  
Set the jumpers as desired according to the table in the [Controls - Jumpers](#jumpers) section.  
Use the ON/OFF Jumper to turn the christmas ball off and on. One christmas ball in the chain should be enough to power the whole chain. If you connect many christmas balls, you might need to use multiple batteries, in this case, make sure to turn all christmas balls with batteries off, to turn the whole chain off and vice versa.  
Like in stand-alone mode, you can use the potentiometers to control blinking pattern and speed, just play around (see [Controls - Potentiometers](#potentiometers) section for details).
