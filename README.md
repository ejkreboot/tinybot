tinybot
=======

Rechargeable, customizable robots inspired by https://hackaday.io/project/581-Tiny-robot-family

NOTE: This initial design is completely untested.  Please verify schematic and board prior to manufacturing boards.

The idea here is to create a education platform for embedded computing and basic robotics.  

A drawback of this design is the use of a few surface mount components.  This is to avoid use of through hole packages for MOSFETs which are relatively large.

This design incorporates a charging circuit.  Plugging in the robot to a USB charger will charge a lithium ion cell inserted into the batter holder.  This circuit is designed to charge at 100mA.

To use the robot, pager vibrator type motors must be soldered to the motor pads (one on the left, one on the right) and then hot glued in place (see https://hackaday.io/project/581-Tiny-robot-family).  The ATtiny must be programmed prior to inserting into the socket (again, see https://hackaday.io/project/581-Tiny-robot-family).

The PCB includes a prototyping area with adjacent power rails to allow adding sensors/actuators to the free pins of the ATtiny.

The ATtiny can NOT be programmed in place with this design (that would require additional circuitry to isolate the ATtiny during programming).  However, the ATtiny can be programmed on a breadboard by an Arduino running the ArduinoISP sketch (see http://www.instructables.com/id/Program-an-ATtiny-with-Arduino/).  

Please lend a hand and correct/improve the design!