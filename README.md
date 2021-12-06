# polyphonic-sequencer-synth

**WARNING: This device could destroy your computer's USB port or USB adapter. This device also flashes at high frequency and is an epilepsy risk.**

A mini sequencer and polyphonic synth based directly on Elliot Williams' epic Logic Noise series from Hackaday (https://hackaday.com/2015/02/04/logic-noise-sweet-sweet-oscillator-sounds/).

The boards were designed and manufactured at Fablab Digiscope in Orsay, France by Jonah Marrs with funding from La Diagonale U Paris Saclay. 

The sequencer portion is an 8-bit looper using a 595 shift register (and a second 595 just to make the corresponding LEDs blink). Bits can be added in LOOP mode by pushing the BEAT button. Beats are automatically added in AUTO mode by synchronizing the CLK and DATA knobs at the far right. The green LED is connected to the CLK frequency. 

The jumpers can trigger one of three notes everytime that corresponding LED flashes. The timber of each note can be varied by turning the pots marked A, B and C.

The notes are passively mixed in a final stage and can be either output to the onboard buzzer or send to the 3.5mm audio out with OUT selected on the second slide switch. 

The board can be powered by USB C or with a 5V power supply connected to the power header. 



