# Soldering Methodology

## THT soldering
Soldering the throughhole components was relatively easy. Set the soldering iron to ~330 - 350 degrees and take some 0.5mm filament.
Thread the component through the assigned hole and bend the wire on the other side to secure the component.
Hold the soldering iron to the hole for a second or two before touching the point with the filament, melting a small amount of solder.
Once finished, cut the excess wire from the component.

One of the challenges with through hole soldering is when you place a component incorrectly, as it's far more difficult to desolder the component as the solder is within the hole. 

I placed a resistor in the wrong place, which required me to pinch the resistor with some fine pliers while soldering the hole from the other side. Once free I had to place the soldering iron on the other side of the hole while threading the wire of the new resistor through.

## SMD soldering

smd soldering is much more difficult than through hole, the components are far smaller and aren't secured with any wires. 

As with through-hole, you set the soldering iron to ~330 - 350 degrees and use 0.5mm filament.

You start by heating a single pad with the iron and applying a small amount of solder. Then you grasp the component with some fine pliers, heat the soldered pad until it melts and then place the component on the pads in the good orientation. This part is the most difficult as the parts are sometimes 2mm wide and even small hand movements can move the component a lot. It requires a lot of patience.

Once the component is oriented correctly and has one pad soldered, continue with the remaining pads by placing the iron on the pad for 1-2 seconds before touching the pad with the solder filament, melting a small amount on the pad (paying careful attention not to bridge connections).

The most challenging part of smd soldering, for me, was soldering the chips as each pin is 0.25mm apart from each other, making it very easy to bridge connections.

This was my main challenge of soldering this board, at one point I had some bridged pins on the atmega and had to desolder them. To do this I had to cover the pins in plenty of flux and apply the soldering iron repeatedly until it melted onto the pads underneath. I found using an up-down motion with the iron helped move the solder in the good direction.
