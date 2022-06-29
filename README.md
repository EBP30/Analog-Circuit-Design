# Analog-Circuit-Design
A compilation of my analog circuit design

Bouncing Ball Detector: a circuit that will reliably produce a single LED pulse every time a 3/8” 
diameter steel ball is dropped Into the heavy plastic base from a height of about 4 inches. Locate the base 
about 6 inches from the sensor, and place it in the provided paper plate to catch the ball. Only one LED 
pulse must be produced with each drop of the  ball, and the ON time must be independent of the audio 
pulse amplitude.

Frequency Detector: Design and build a circuit which will light a #194 lamp when the frequency of an input sinewave 
(from a function generator) is OUTSIDE of 1600 Hz to 2400 Hz, +/- 10%.  The lamp must be OFF when the 
frequency is within these limits.

Function Generator: Design a “Function Generator” that produces sine, square, triangle, and pulse waveforms.  A sketch of 
an imaginary front panel is shown below

<img width="696" alt="image" src="https://user-images.githubusercontent.com/100106103/176330531-3770ffd9-e5bc-459b-a035-b7e4bf64ce70.png">

Sine, triangle, and square wave outputs: 0 to 20Vpp, adjustable with the “Amplitude” control.  Source and sink 
50mA.  Rise and fall time of the square wave is to be < 100usec, measured with .01μFd across output

Pulse Output:  0 to 10Vpk.  Source and sink 200mA.  Rise and fall time of the pulse waveform is to be < 100 
nsec,  measured  with  1000  pFd  across  output.  The Pulse Output has its own “Amplitude” control.  The “Duty 
Cycle” control applies to the pulse waveform only, and should adjust from approximately zero to 100%. 
