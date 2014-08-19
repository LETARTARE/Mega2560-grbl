=======================================================================

Grbl with Code::Blocks

This directory 'devGrbl\CodeBlocks' contains the last versions  July 29, 2014

================================================================================

These are projects Code::Block to build Grbl-xxx

August 19, 2014 : Grbl-8c1-c and Grbl-8c2-c -> BUG FIXED FOR using V,W or B, C

================================================================================

A- OFFICIAL VERSIONS updated from the site Grbl : 3 axes

A1- Grbl-8cUno-c       : grbl-0.8c for Uno328p 115200 bauds  3 axes

A2- Grbl-9dMega2560-c  : grbl-0.9d for Mega2560 115200 bauds  3 axes  dev !!

A3- Grbl-9dUno-c       : grbl-0.9d for Uno328p 115200 bauds  3 axes   dev !!

A4- Grbl-8cMega2560-c  : grbl-0.8c for Mega2560 115200 bauds  3 axes

A5- Grbl-9eMega2560-c  : grbl-0.9e for Mega2560 115200 bauds  3 axes  dev !!

A6- Grbl-9eUno-c       : grbl-0.9e for Uno328p 115200 bauds  3 axes   dev !!


A7- Grbl-9fUno-c       : grbl-0.9f for Uno328p 115200 bauds  3 axes   edge !!

A8- Grbl-9fMega2560-c  : grbl-0.9f for Mega2560 115200 bauds  3 axes  edge !!

	NEW  : compilable directly with the Arduino IDE

A9- Grbl-9gUno-c       : grbl-0.9g for Uno328p 115200 bauds  3 axes   edge !!

A10- Grbl-9gMega2560-c  : grbl-0.9g for Mega2560 115200 bauds  3 axes  edge !!


================================================================================

B- UNOFFICIAL VERSION from the old version 0.81 : 4 axes for MEGA2560

B1- Grbl-81-c   : grbl-0.81 for Mega2560 57600 bauds  4 axes  X, Y, Z, C
                
                - is a copy of an old website disappeared Sept. 19, 2013
                    https://github.com/EliteEng/grbl
                who recently reappeared in but with a copy of official Grbl-0.8c .

B2- Grbl-82-c   : grbl-0.82 for Mega2560 57600 bauds  4 axes  X, Y, Z, C
                
                - is an adaptation of 'grbl-0.81'
                - correcting wrong sized tables in limits.c, main.c, nuts_bolts_h, settings.c
                - on a proposal from DavidLQuick modifcation of protocol.c

B3- Grbl-83-c   : grbl-0.83 for Mega2560 57600 bauds  4 axes  X, Y, Z, C
                
                - with M3, M4, M5 and M7, M8, M9 functioning properly active low (configurable in "config.h")
                     
B4- Grbl-84-c   : grbl-0.84 for Mega2560 57600 bauds  4 axes  X, Y, Z, A
                
                - axis C (about Z) ->  ? A (around X)
                - by infobarquee and icare : french forum "http://forum.arduino.cc"

B5- Grbl-843-c  : grbl-0.843 for Mega2560 57600 bauds  4 axes  X, Y, Z, A
                
                - configurable in 'defaults.h':
                - axis A rotary in [-360.0..360.0] degrees
                - machine definitions : steps motor, pitch screw, microsteps, worm gear ratio

B6- Grbl-844-c  : grbl-0.844 for Mega2560 57600 bauds  4 axes  X, Y, Z, T
                
                - with T in [A, U]
                - choice axis : A (rotary) or U (linear)

B6- Grbl-845-c  : grbl-0.845 for Mega2560 57600 bauds  4 axes  X, Y, Z, T

                - with T in [A, B, C, U, V, W]
                - rotary (A, B, C) or linear (U, V, W)
                - use "GrbController-3.6-1"

To interact with Grbl 4 axes from  "https://github.com/zapmaker/GrblHoming"


B7- Grbl-8c1-c  : grbl-0.8c1 for Mega2560 57600 bauds  4 axes  X, Y, Z, T
	August 19, 2014 : BUG FIXEDusing V,W or B, C

                - it's official 0.8c + ...
                - with T in [A, B, C, U, V, W]
                - rotary (A, B, C) or linear (U, V, W)
                - use "GrbController-3.6-1-T1.."
                 https://github.com/LETARTARE/GrblHoming/tree/Letartare/GC-3.6.1-T1

B8- Grbl-8c2-c  : grbl-0.8c1 for Mega2560 57600 bauds  4 axes  X, Y, Z, T
	August 19, 2014 : BUG FIXEDusing V,W or B, C

                - it's official 0.8c + différent pinout for 4 axes
                - with T in [A, B, C, U, V, W]
                - rotary (A, B, C) or linear (U, V, W)
                - use "GrbController-3.6-1-T1..T4"
                 https://github.com/LETARTARE/GrblHoming/tree/Letartare/GC-3.6.1-T1..T4


================================================================================

For any problem use "issues"

================================================================================






