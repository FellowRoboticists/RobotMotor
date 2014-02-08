RobotMotor Arduino Library
==========================

This is the Arduino library provided with the Robot kit. It provide a medium-level
abstraction above the Adafruit motor shield library. 

It has been modified somewhat from the version provided with the kit; primarily 
tuning parameters.

Building/Testing
================

Preparation:

1. Determine the directory in which you will place the RobotMotor project
2. Clone the https://github.com/FellowRoboticists/arduino-tasks project. This provides the necessary ruby tasks use by the rake command.
3. Clone the https://github.com/FellowRoboticists/RobotMotor project.
4. In the RobotMotor project directory, invoke the 'rake' command. This will automatically pull all the dependency libraries from GitHub and prepare the ino project for building.

To build the example sketch:

```
ino build
```

To upload the example sketch:

```
ino upload
```

Copyright
=========

Copyright Michael Margolis May 8 2012

Copyright (c) 2013,2014 Dave Sieh

See LICENSE.txt for details.
