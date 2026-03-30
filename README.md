Introduction
This is an ergonomic split keyboard that I designed to match the shape of my hands.
It is designed this way to hopefully reduce strain on my wrists and hands when typing.
I like making stuff.
I also just think that split keyboards are cool.
It uses the Seeeduino XIAO BLE nRF52840.
It has bluetooth communication capabilities and has a USB-C port.

Image
<img width="1092" height="612" alt="image" src="https://github.com/user-attachments/assets/817218c6-bb25-4918-a070-193caee5ebe7" />
Above is my Split keyboard design on Fusion360.

Status
I have designed everything (hopefully) like the firmware, PCB and schematics.
I have also created the BOM.
I will start assembly when it is approved and i buy the parts needed.

BOM
Name	                     Purpose	                          Units Total	            Total (USD)    	Distributor
Male header pin row        For soldering Seeeduino to PCB    	1     	                $1.31	          AliExpress
Battery	                   To supply power                   	1	Pair                  $9.18	          AliExpress
Screws                   	 Secure keyboard parts	            1 Pack	                $1.31	          AliExpress
Mounting screws	           Secure PCB in place	              1 Pack	                $0.74	          AliExpress
Threaded insert	           Housing for screws               	1 Pack                	$1.64	          AliExpress
PCB	                       Main circuit board               	1 Pack                	$14.38	        JLCPCB
Diodes	                   Direct current one way            	1 Pack	                $5.57	          AliExpress
Hall sensors	             Magnetic detection 	              3 Packs	                $11.51   	      AliExpress
Magnets                    Connect halves together	          1 Pack                	$1.31         	AliExpress
Sliding Switches           Power On/Off                     	1	Pack                  $5.10          	Amazon
Stabilizers                Support for larger keycaps	        2	                      $4.44	          AliExpress
Key Switches	             Register key strokes	              1 Pack                	$45.27         	AliExpress
Seeeduino (2pcs)         	 Main controllers	                  1 Pair	                $38.42        	AliExpress
Keycaps	                   Key labels	                        1 Set                 	$16.79	        AliExpress

Assembly instructions
1. Solder the diodes and hall sensors.
2. Solder the male header pins onto the seeeduino.
3. Link the seeeduino to the firmware on ZMK.
4. Solder the other side of the male header pins onto the PCB.
5. Screw the stabilizers into the PCB.
6. Solder the wires of the battery to the bat pins of the microcontroller and the sliding switch.
7. Place the battery into the small cavity in between the case and where the PCb is meant to go.
8. Screw the sliding switch into the side.
9. Insert the brass threaded insert into the 3d printed case in the middle and on the rim by heating the inserts and pushing them in.
10. Screw in the five mounting screw in to the middle.
11. Place the PCB on top and screw the black screws in.
12. Glue the magnets into the holes in the 3d printed case.
13. Click the key Switches into the plate.
14. Screw the plate on the bigger portion of the case.
15. Click the keycaps into place.
16. Repeat for both halves.
17. Pair both the halves together.
18. Test the keyboard.
I have not actually built the keyboard yet.
