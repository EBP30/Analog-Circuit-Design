# Analog-Circuit-Design
A compilation of my analog circuit design

## Bouncing Ball Detector 
Built a circuit that produces a single LED pulse every time a 3/8” 
diameter steel ball is dropped onto the heavy plastic base from a height of about 4 inches. Only one LED 
pulse is produced with each drop of the  ball, and the ON time is independent of the audio 
pulse amplitude.

## Frequency Detector 
Designed and built a circuit which lights a #194 lamp when the frequency of an input sinewave 
(from a function generator) is OUTSIDE of 1600 Hz to 2400 Hz, +/- 10%.  The lamp is OFF when the 
frequency is within these limits.

## Function Generator 
Designed a “Function Generator” that produces sine, square, triangle, and pulse waveforms.  A sketch of 
an imaginary front panel is shown below:

<img width="696" alt="image" src="https://user-images.githubusercontent.com/100106103/176330531-3770ffd9-e5bc-459b-a035-b7e4bf64ce70.png">

Sine, triangle, and square wave outputs: 0 to 20Vpp, adjustable with the “Amplitude” control.  Source and sink 
50mA.  Rise and fall time of the square wave is < 100usec, measured with .01μFd across output

Pulse Output: 0 to 10Vpk.  Source and sink 200mA.  Rise and fall time of the pulse waveform is < 100 
nsec,  measured  with  1000  pFd  across  output.  The Pulse Output has its own “Amplitude” control.  The “Duty 
Cycle” control applies to the pulse waveform only, and adjusts from approximately zero to 100%. 

## Mixed Signal Modulator/Demodulator 
Designed a circuit that produces a PWM waveform that will be the digital representation of an input 
signal. This waveform is sent over a transmission channel to a receiver/converter which reconstructs the original signal.
The transmitter and receiver will be coupled by an opto coupler which substitutes for an optical fiber link or other digital transmission channel. 

<img width="718" alt="image" src="https://user-images.githubusercontent.com/100106103/176565000-a7e02cd5-05c3-4c59-b868-302c326bd116.png">

## Lamp Dimmer and Flashing circuit 
Designed and built a triac phase-control lamp dimmer that will drive a #194 lamp with full-wave AC.  
Use the “13VAC” transformer as the only power supply; a separate power supply is not to be used to 
power  the  control  circuitry. Lamp  brightness  is  to  be  controlled  by  a  potentiometer  and  must  be 
adjustable  from  completely  OFF  to  full  ON. The flashing feature of the circuit does not simply turn on and off the power source but slowly dims to no brightness and full brightens with this control signal.
<img width="833" alt="image" src="https://user-images.githubusercontent.com/100106103/176565368-e08072bd-5a7a-4ca6-b50d-ab6fb380af69.png">

## Motor Speed Controller 
Built analog closed loop PID controller to act as a speed contoller often found in cruise control. Design included in addition to the circuitry a hand build digital encoder made from and IR LED and IR reciever to act as the speed basis to close the loop and measure motor speed.  The controller used PWM modulation to drive the switching speed of the power mosfet to ultimatly control the speed of the motor.

## Tracking Servo 
Built servo controller with attached laser to find center of solar panel no matter where solar pannel i place within a 5ft radius of laser. The laser has a functionality of a searching mode in where it searches for solar panel, a found mode where it tracks the panel and a override feature that jogs the laser left and right. 

## Switch Mode Power Supply
Built a Buck converter with feedback control. The circuit has an input voltage from 16-28V and a variable ouput voltage of 5-15V adjusted through a potentiometer. 
