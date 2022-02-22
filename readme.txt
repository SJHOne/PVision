This is a C++ library for Arduino for controlling a Pixart sensor from a WiiMote over I2C.

Installation
--------------------------------------------------------------------------------

To install this library, just place this entire folder as a subfolder in your
Arduino/lib/targets/libraries folder.

When installed, this library should look like:

Arduino/lib/targets/libraries/PVision              (this library's folder)
Arduino/lib/targets/libraries/PVision/PVision.cpp  (the library implementation file)
Arduino/lib/targets/libraries/PVision/PVision.h    (the library description file)
Arduino/lib/targets/libraries/PVision/keywords.txt (the syntax coloring file)
Arduino/lib/targets/libraries/PVision/readme.txt   (this file)

Building
--------------------------------------------------------------------------------

After this library is installed, you just have to start the Arduino application.
You may see a few warning messages as it's built.

To use this library in a sketch, go to the Sketch | Import Library menu and
select PVision.  This will add a corresponding line to the top of your sketch:
#include <PVision.h>

To stop using this library, delete that line from your sketch.

Geeky information:
After a successful build of this library, a new file named "PVision.o" will appear
in "Arduino/lib/targets/libraries/PVision". This file is the built/compiled library
code.

If you choose to modify the code for this library (i.e. "PVision.cpp" or "PVision.h"),
then you must first 'unbuild' this library by deleting the "PVision.o" file. The
new "PVision.o" with your code will appear after the next press of "verify"
