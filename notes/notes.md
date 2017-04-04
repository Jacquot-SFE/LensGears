Notes On Designing Lens Gears
====

I'm using Inkscape for the lens gear design.  It has a gear generator tool that helps a bit.  It's not so helpful in a few regards, too.

* It's calibrated in pixels, 90 to the inch.  
* Not all programs agree on the pixel density, so transporting files may be problematic.  I think Corel uses 96 pix per inch.  
* The gear generator is also calibrated in pixels.

Gear generator is in Extensions->render->gear.
Set it as follows

* Teeth to fit diameter.
	* 80 teeth makes 2.5" pitch diameter
	* 100 teeth makes 3.125" pitch diameter
	* 128 teeth makes 4" PD.
* 8.835 pitch
* 20 degree pressure angle

I've been verifying some of my gear dimensions against  [Actobotics Gears](http://www.servocity.com/html/32_pitch_hub_gears__1__bore_.html).


## Gear Background

0.8 pitch is equivalent to 32 pitch.

32 pitch means 32 teeth on a 1" PD gear.  Thus 64 teeth is 2", 128 is 4"

Pitch diameter is the effective size of the gear, the average between the high and low spots of the teeth, or the size of an equivalent smooth wheel.  Outside diameter (OD) is a tiny bit larger.

## Lens Info

[mir.com.my](mir.com.my) has a bunch of information about old lenses, sometimes including mechanical drawings.  

### Specific Lenses

#### Nikon

I've mainly got Nikon/Nikkor glass, so that's what I can measure.

##### Nikkor-N 24mm f/2.8

Measures 2.5455" across widest part of focus ring (approx 64.6557 mm).

[](http://www.mir.com.my/rb/photography/companies/nikon/nikkoresources/6070nikkor/wides/24mmf28.pdf)

##### Nikkor-S 50mm f/1.4

Measures 67.10 mm across widest, fluted, part of focus ring.  That area is about 6mm deep, and there are 12 large flutes total, each mesa of the flutes has 10 little flutes.  Focus ruing moves forward by about 4mm as turned.
