# Noise, Clock and S&H

This module is a sort of 3-in-1 module, containing 4 types of noise, a clock generator based on a 555 IC and a sample-and-hold section. It’s based on / inspired by the Noise & S&H module by Niklas Ronnberg. It has a slew function, which is really nice, use it quit a lot.

The noise colors are White, Blue, Pink & Red. They are created by filtering the white noise. There are 2 trimmer pots on the back, one to set the overal noise volume and one to set the pulse length of the clock output.

## Status: Finished

- done: first schematic & board design
- done: breadboard and test
- done: design frontpanel
- done: order PCB and build prototype

## Pot Values

Since the earlier schematic didn't include the pot values, here they are (schematics have also been updated)

Slew & Attn: 100k lin
Rate: 1M log