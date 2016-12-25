<p align="center">
  <img src="https://raw.githubusercontent.com/PitBarber/ArduSnake/master/DFE27753-16EA-4046-82B0-1DEAE4ECBF42.jpg" width="500"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/PitBarber/ArduSnake/master/ArduSnake.gif" width="500"/>
</p>


# ArduSnake
classical game of Snake implemented in arduino using led matrix and 74hc595 shiftRegisters

the objetive of this proyect is to create a portable console with this game or another classical games,
using less as possible digitalPorts of arduino,2xsifhtRegisters,2xbuttons and music. 
Why? because i want to use tiny as possible IC from arduino family.

Power  will be a 3.3V, with this voltage we can use the 8x8 led matrix without resistors, this is good because we will have less power consumption, i want to use 2AA batteries.

I will use a DC-DC to rise voltage up to 3.3V, maybe TPS61291, my objetive is: 10hours of game with 2AA batteries.

thank you for stay here reading this and be interested in mi proyect! :D

# Scheme

<p align="center">
  <img src="https://raw.githubusercontent.com/PitBarber/ArduSnake/master/ArduSnake%20Scheme.PNG" width="900"/>
</p>

Here you have how all is connected, i've added some capacitors near the 74hc595's VCC pin, sometimes, when i push the buttons i have some issues, and i've added these capacitors to give the drivers an stable power feed.
You can't see this modification in the schematic, but is seen in the ProtoboardBuiltIn photo
