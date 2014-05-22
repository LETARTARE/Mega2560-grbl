=======================================================================

Grbl with Code::Blocks

This directory 'devGrbl\CodeBlocks' contains the last versions  May 22, 2014

================================================================================

These are projects Code::Block to build Grbl-xxx

================================================================================

A- OFFICIAL VERSIONS updated from the site Grbl : 3 axes

A1- Grbl-8cUno-c       : grbl-0.8c for Uno328p 115200 bauds  3 axes

A2- Grbl-9dMega2560-c  : grbl-0.9d for Mega2560 115200 bauds  3 axes

A3- Grbl-9dUno-c       : grbl-0.9d for Uno328p 115200 bauds  3 axes

A4- Grbl-8cMega2560-c  : grbl-0.8c for Mega2560 115200 bauds  3 axes

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
================================================================================

For any problem use "issues"

================================================================================






