# pcb-puzzle-cube
Mechanical, Optical, &amp; Electronic Puzzle Cube

I made a puzzle cube for my wonderful electronics lab instructor who is also a professional trumpet player! A lot of the fun in making this was designing my circuits and mechanical components around 5 milled PCBs soldered together into a cube. Puzzles involve "playing" a sequence of notes on a flex PCB capacitive trumpet and using a butterfly flexure to align a laser path through a beamsplitter.

## Milled PCBs
From left to right, the sides of the cube include: 
1. WS2812b LEDs 
2. resistor combinations with pads for probing
3. laser diode regulated by a LM317 circuit and switched on/off electronically with a 2N7002 MOSFET 
4. QTPy ESP32 microcontroller
   
Sides 1 & 4 also include a photoresistor to detect laser beam alignment.

And the bottom:

5. 5V power jack, switches for the board power and laser power, mount for butterfly flexure
   
![image](https://github.com/user-attachments/assets/9367be02-4c88-413f-806b-306db8a76b6d)

## Trumpet Capacitive Touch FlexPCB
I really wanted an excuse to fab a flexPCB, so I did so here. FlexPCB files are located in the <code>trumpet</code> subfolder. 

The connector end of the trumpet was designed to fit in a 6pin/1mm FPC connector. I ended up just soldering it directly to the board though, since I ended up finding an end mill small enough to carve out the 1mm pitch pads. It also helped me avoid buying an extra component. 

![image](https://github.com/user-attachments/assets/bc017b18-ee25-447b-bcfc-bc9ad5ee92e7)

## Video Demo
Watch a video demo of the cube being solved [here](https://www.youtube.com/watch?v=AHTcb9tr4TA) :D



