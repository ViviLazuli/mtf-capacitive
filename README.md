# MtF122 Capacitive Conversion PCB for IBM Model M 122-key Keyboards

### Rev. 2 / Rev. B

This version is in prototyping phase. However, it does function.

It has only been tested with a late thin-bezeled variant of the M122. The screw holes have a tight fit and may require widening and more clearance around them for traces.
!The screw holes may not be in the correct positions for other M122 variants!

Capacitive pad measurements are taken from i$/idollar's FSSK and FEXT PCB designs, which I believe are directly measured from the original Model F PCBs.

The PCB thickness should be 0.6mm. This is thin enough to allow the board to flex into shape without preforming it with heat and duct tape (which I couldn't make work anyway).

Standard glossy soldermask is probably the best choice. JLCPCB has had issues with wear on their black soldermask before. They have changed the formula, but a standard green/red/blue/yellow/purple/white/etc. glossy solder mask is probaby the safest bet for keyswitch wear resistance.
Higher wear resistance might also be achieved by coating the front of the capacitive pads in silkscreen, as silkscreen is an extra layer of epoxy. I am unsure how this will affect keyfeel or actuation, however.

There is a bullseye circle on the front of the board. This is for drilling a hole for a trackpoint module. There are redundant traces to allow for safer drilling at this location, but this functionality has not been tested!

The diameter of the copper around the connecting pads could be to be enlarged. They are too fragile and I had one rip out when disconnecting a mill-max pin header connector (fortunately it was just a redundant ground).

For connecting the board to an xwhatsit or other controller, I would recommend 3M 8132/06 100, which has the correct pitch for this board and xwhatsit:
https://www.digikey.com/en/products/detail/3m/8132-06-100/7809902

The key matrix of the PCB is reverse-engineered from photos of original F122 PCBs and should be exactly the same. The connector is likely in a slightly different position though.

The screw hole placement was prototyped with paper by printing an SVG output of the board edge cuts and drill holes on multiple sheets of paper, pasting them together, cutting out the paper 'PCB', and hole punching the drill hole locations. A few iterations of this paper prototyping method allowed me to test hole locations and board fitment against the barrel plate without having to make an entire PCB first.

I did not clad the steel backplate in tape before mounting the PCB. The solder mask should provide adequate isolation. Just make sure the steel is clean and there are no burrs/jagged edges that could scrape the PCB.

Please read LICENSE.txt for the full MIT License.

Some photos are here for reverse-engineering reference only and are not mine nor included under the license.

Design by ViviLazuli, 2020.
