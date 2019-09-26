# COTS
This code provides an interactive demo of some of the COTS functionality as described in the TOG-ACM paper:
"Corner-Operated Tran-Similar Maps, Patterns, and Lattices" by Jarek Rossignac.

This is a Processing sketch.
Below is a script for installing and using the sketch:

GUIDE FOR USING THE COTS SKETCH
Jarek Rossignac
Georgia Tech

Download Processing from https://processing.org/download/ and install it
Double-click on one of the .pde files in COTS to start this sketch
Press the play button (black triangle in grey disk)
Follow the demo sequence of key actions suggested at the bottom of the menu.
	Click in the canvas to activate the window
	Press SPACE to hide the menu (you can open Menu.png to see the menu and the canvas where you play with COTS)
	You should see blue stars
	move the mouse (without pressing it) to see the map inversion at work (shows iso-curves through mouse location)

	play with the map by clicking near a corner point (a,b,c,d)  and dragging it (move the mouse while it is pressed)
t	and click&drag mouse to translate the four control-corners
z	and click&drag mouse towards/away from the center of the quad to shrink/grow it (or use scroll-wheel on the mouse)
* 	hide the star-matrix
p	deactivate showing iso-curves through the mouse that demonstrate inversion
T	to see a checkerboard

f	hide the fixed point f
l	hide the labels of the ocntrol points
….	increase cell counts by 4
	play with the map by repeatedly clicking near a corner point and dragging it
T	hide the checkerboard
o	show the warped image of a circle in each cell
#	hide the grid of iso-curves

	play with warping the circle-matrix by repeatedly click&dragging corners 
o 	hide the magenta circles
x	show the COTS texture map of a picture 
	play with the warp by repeatedly by repeatedly click&dragging corners
x	hide the texture

#	show the grid again
,,,,	decrement cell counts by 4
d	display disk-matrix
@	show control circle (magenta) for disks
	click&drag its center (brown point) and radius-marker (magenta point) 
	make the circle small and centered in the corner cell incident on the red control corner 
h	show display beams (notice that border beams are not trimmed) 
	adjust the beam-width using the radius-marker (magenta point on the control-circle) 
#	hide the grid
b	hide the border iso-curves
….	increase cell-count
	play with this simple COTS lattice by repeatedly by repeatedly click&dragging corners
~	save an .pdf image of the canvas in COTS/IMAGES/PICTURES_PDF (does not save texture maps)

h	to hide the beams
d	to hide the disks
#	to show COTS grid
e	to show the grid of the non-exponential version, which is non-TS 

e	to hide it
c	to show the grid of the Coons patch computed from the COTS border
#	to hide COTS grid
b	to show the border
	repeatedly click&drag corners to create a configuration where that map folds over itself
c	to hide it the Coons grid
#	to show that the COTS map with the same border does not fold

S	to save the current configuration
	edit one of the corners by click&dragging it
L	to load the saved version
O	to see the COTS image of a circle passing through the four corners in parameter space

O	to hide it
,,,,,	to have a 4x4 grid of tiles
l	to display the corner names
	bring (b) and (c) close to each other near the center of the screen
	drag (d) to wrap around them and bring it close to the mid-course point on the border between (a) and (b)

222	will help you align (d) with the mid-course point
t	and click&drag, if needed, to center the map
T	to show the checkerboard coloring of tiles
lb#	to hide the corner names, the border, and the iso-curves


….	to increase the cell count to 8x8. Notice the seamless alignment of the cell borders along the junction 
….	produces another seamless alignment
	Try other seamless swirls (using 3x3, 5x,5 or 7x7 grids and ‘3’, ‘5’, or ‘7’ keys to help with alignment)
	Press ‘0’ to remove all swirls and restart with a non-swirling map
d*	to show the disks and the stars at iso-curve crossings
	adjust the green disks using the control-circle center and radius-point (‘@’ to show/hide it)

