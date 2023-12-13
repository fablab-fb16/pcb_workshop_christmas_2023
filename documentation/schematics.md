# Schematics

Two timers generate a square-wave signal (freqency independatly variable by potentiometers, see /notebooks folder for Jupyter notebook on frequency range calculation).

These two signals are used on data and clock input of shift register to create output patterns. Each output of the shift register is connected to one LED.

The Jumpers are used to select signal source and output source for daisy-chaining multiple boards. See [Usage Instructions](/documentation/Usage%20Instructions.md) for more info on this.

## Main Circuit
![](/documentation/schematics/root_schematics.png)

## Timer (Data)
![](/documentation/schematics/timer.png)

## Timer1 (Clock)
![](/documentation/schematics/timer1.png)
