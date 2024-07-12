# gpsdData
![piSyncdWithGPS](/images/pyGpsSyncdWithNewAntenna.gif)
Experiments with rPi0, python, ulitmate GPS board, etc

- So, I created this as a project to try and add GPS tracking to A/V equipment to avoid theft. It was done
  completely 'open-source' with a Raspberry Pi, and a GPS board (see attached pictures)

- the plan was to translate the received NMEA messages to a 'tuple', add a local, temporary datastore, updating this to a central DB of some sort,
  and a visual-interace to the server which could display a visual representation of where the equipment was at any one time.
- There are questions about the security aspects of relying open-source hardware, as well as the accuracy of using GPS inside buildings.
  
I started with just regular Python code, added Flask, tried quart, added tests/experiments, and finally async,
incorporating all these as submodules.

see ./images/ directory for more pictures
-jps
