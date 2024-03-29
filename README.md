# polyphonic-sequencer-synth

**WARNING: This device could destroy your computer's USB port or USB adapter. This device also flashes at high frequency and is an epilepsy risk.**

*NOTE: Not all 74HC14 ICs work for this circuit. Elliot Williams uses the CD40106BE instead. Make sure your 74HC14 has Schmitt trigger with hysteresis and maybe order a couple different brands to be sure. I find that Nexperia ICs work well and not I have had bad luck with Diodes Incorporated.

A mini sequencer and polyphonic synth based directly on Elliot Williams' epic Logic Noise series from Hackaday (https://hackaday.com/2015/02/04/logic-noise-sweet-sweet-oscillator-sounds/).

The boards were designed and manufactured at Fablab Digiscope in Orsay France, which is run by Romain Di Vozzo, by Jonah Marrs with funding from La Diagonale U Paris Saclay. Here's a video of the workshop and the board in action: https://vimeo.com/653720316

Selena Pere has made an beautiful inferface for a version 2 of this device. 

The sequencer portion is an 8-bit looper using a 595 shift register (and a second 595 just to make the corresponding LEDs blink). Bits can be added in LOOP mode by pushing the BEAT button. Beats are automatically added in AUTO mode by synchronizing the CLK and DATA knobs at the far right. The green LED is connected to the CLK frequency. 

The jumpers can trigger one of three notes everytime that corresponding LED flashes. The timber of each note can be varied by turning the pots marked A, B and C. 

The notes are passively mixed in a final stage and can be either output to the onboard buzzer or send to the 3.5mm audio out with OUT selected on the second slide switch. 

The board can be powered by USB C or with a 5V power supply connected to the power header. 

Notes:
-For the device to make predictable sound, there should be at least one jumper going to notes A, B and C from the loop sequence header. 
-If the clock is set too fast it will saturate the shift register resulting in a full set of beats. To remove the beats, turn to AUTO mode and find a combination of CLK and DATA that produces no beats, and then switch back to LOOP mode once the beats have been cleared to make your own pattern. 
-You have to push down hard enough to activate the mini metal button and if the clock is going super slow it might seem likes it's impossible to add beats. Either speed up the CLK or hold the button longer than you would expect is necessary :).
-If you change the output mixing resistors you can change the output volume. 


