# How to Build a Syringe Pump

- **[Home](/Syringe-Pump/index)** 
- [Mechanical](/Syringe-Pump/mechanical)
- [Electrical](/Syringe-Pump/electrical) 
- [Code](/Syringe-Pump/code) 



## Specifications of Syringe Pump.

Building a syringe pump comes with many advantages. Foremost, it is much more inexpensive than buying a 3D printer syringe pump for a new printer design outright. It also is a fun learning experience, where one can learn 3D computer aided design, electrical circuits, and hands on building. Presented here is a syringe pump modeled and assembled in Fusion360, and then electrically wired via Arduino to move the pump.

The resolution of the syringe pump is dictated by the speed at which the motor moves, which is controlled by step size and thread angle. A slower speed allows for higher resolution, while a faster speed will yield a lower resolution print. The total number of steps per rotation that can be programmed into the pump is 16, and the threaded rod is 200mm in length. This gives a total of 3200 steps, and with a thread size of 1.25mm. Taking these variables and the volume of the syringe into consideration, it can be estimated that the resolution from the syringe is about 11uL per step. 


The two variables that determine maxiumum flow rate are largest RPM produced by the motor and the pitch of the threaded rod. Maximum ideal flow rate would be rotations per minute multiplied by the pitch (1.25mm), however, this does not account for the friction produced between the threaded rod and the nut. Therefore, this friction is the limiting factor in determining maximum flow rate.


