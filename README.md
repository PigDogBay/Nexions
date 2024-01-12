# Nexions
ZX Spectrum Next Shoot'em Up with inspiration from the golden age of games
  \
You can download the latest binary package from the Releases page, grab the Nexions.run.zip and unzip onto you Next SD Card. Using the Next browser click on Nexions.run

To build,   \
Unzip the latest source code release and copy the nexions folder to your home (or games) directory on the Next SD Card
  \
  \
ENTER ZX Spectrum Next BASIC  \
.cd into the nexions folder  \
.txt2build nexions.txt  \
.txt2build starfield.txt  \
.txt2build build.txt  \
  \
Main game code:  \
LOAD "nexions.bas"  \
  \
Starfield image generator  \
LOAD "starfield.bas2"  \
RUN  \
starfield.sl2 will be created  \
  \
build.bas is used for development, it syncs the nexions directory with your PC and converts nexions.txt to basic.
  \
  \
MPD Bailey Technology 2024.
