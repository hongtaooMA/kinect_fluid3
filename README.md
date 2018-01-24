# A magical mirror project # kinect_fluid

![](https://github.com/hongtaooMA/kinect_fluid3/blob/master/001.jpg)

Dependancy: 
1. Kinect 2.0, SDK version: https://github.com/shiffman/OpenKinect-for-Processing
2. Pixelflow Library for Processing: http://thomasdiewald.com/processing/libraries/pixelflow/
   with specific libs Pixelflow depended on
3. A projector/big enough screen, a computer with decent GPU
Make sure you could run the Kinect and Pixelflow examples before running kinect_fluid

Perfect for Halloween party.

![](https://github.com/hongtaooMA/kinect_fluid3/blob/master/008.jpg)

Run kinect_fluid3.pde directly to test the program, and adjust the position of kinect until you find the screen a mirror of reality.

Fine tunes and effects:
1.  fluid.param.dissipation_density     = 1.00f; // How dense the particle field is, do not exceed 1.2, or weird bug emerges
2.  fluid.param.dissipation_velocity    = 0.95f; // How fast the particle dissipate, faster the less obvious is the effect
3.  fluid.param.dissipation_temperature = 0.70f; // How strong the particle float, faster the particle go above
4.  fluid.param.vorticity               = 0.50f; // Generally how fast the particle update

No license, no warranty, use as you like.
