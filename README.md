# coin-spinner
**Coin spinning conveyor with top and bottom cameras**

When finished... this rig will have 2 independent stepper controlled belts with a gap in the middle with cameras on top and bottom. The idea is this can use very cheap USB microscope webcams to scan and hunt for very close up rare coin features. This about as cheap as it gets with still being able to do things like determine the exact stage of a documented die in an automated fashion. 

**Preliminary Tasks**
* Add the bottom camera
* Build a camera mount for the temp rig
* Make a network for one coin and determine where the coin is. 
* Write software to drive the coin around in real time. No question this is going to have to compensate on the fly. Capture,calc next move, Capture

**Design a new coin spinner conveyors:**
* Don’t share shafts (They could) 
* Use bearings instead of teflon on the other side, so shaft heights are the same. 
* Use one 6mm middle rail that is two parts because there needs to be room for the camera
* 8mm wide Hole in the top plate under the viewing section
**The motors have both a torque and speed problem:**
* Still look for larger motors or higher speed? 
* Larger shaft or printed pulleys
* 22mm belting
* shorter conveyors will cut the torque in half. 
* Bearing on free side. 
* Coin sizes? 
* Layout & Belt sizes? 
* How long would it take to scan using 640x480 with a 2200 diameter image?
* 5.5mm at 640 pixels = 116.4 pixels/mm
* 2211 pixel diameter for a 19mm cent. 
* Hunting will be way quicker than scanning
