# SoOpera

generic SoOp simuator that's focused on the what if's. It's moduler

So the what if would be a ballon platform - grab all the GPS TLE"s. 
figure out specular point locations & sizes
do link budget.
simulate the analog front end and digital back end. 
Have the ability to do 1 or 2 antenans. 
have the ability to set up the back end for a bunch of different delays, etc.

But write it in a way it's moduler. 
so I can do flat earth if tower or low alt balloon
I can do some scattering model if needed
BUT it always comes back to a bitstream at an antenan(s) so we can do the retrevial.

## High Level SoOp Componenets
Transmitter
- Signal (bandwidth, channels)
- Location (airborne, tower, orbit), number of transmitters

Reflection/Scattering
- Type of Reflection
- Surface Properties
- Location of Reflection

Receiver
- Sensor Charachteristics
- No. Antennas
- Location
- No. Receivers
