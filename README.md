# Adaptive Illumination System for Motor Vehicles
Sensing the opposite vehicles bright head lights
automatically makes our vehicles bright lights DIP –but for few seconds only.
Immediately after the crossing of the opposite vehicle, the light will come to bright
position automatically. This function will be repeated for all the vehicles coming in the
opposite direction. Dipping will result in smooth experience for
drivers and negligible risk of accidents. Those vehicles fitted with device are almost
out of the risk of accidents, because by giving signal our vehicle area and road gap
will be cleared to the opposite vehicles fitted with device are almost out of the risk of
accidents, the opposite vehicles for clear road negations. In the present system we
have two sections viz. Transmitter and the Receiver.
In the Transmitter section, LDR is used to sense the high beam or low beam from the
opposite vehicle. As soon as the LDR senses there is hoigh beam of the opposite
vehicle’s headlight it sends the message to the microcontroller PIC18F458.
Microcontroller then initiates the blueetooth module HC-05. Blueetooth HC – 05 is
used as a communication media between the two vehicles. HC – 05 is configured in
Master mode for transmission. It then transmits its signal to the receiver of the
opposite vehicle.
In the receiver section, HC – 05 is configured in the Slave mode for reception. The
transmitted signal is received by the HC-05 module and it is given to the
microcontroller. The microcontroller then accordingly switches the output leds ; to
upper and dipper and after the delay is over the dipper led is again turned ON.The
default condition considered here for the system is that the oppsite vehicle’s headlight
is always at Upper position. 

<img width="533" alt="Screen Shot 2022-02-03 at 3 27 53 PM" src="https://user-images.githubusercontent.com/98929080/152423570-8736605d-8d49-4d34-a8a1-25ee2300a586.png"> 
                Experimental Setup
