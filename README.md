# Swervy

This is a test robot to try and figure out swerve drive, particularly with the YAGSL framework

## Physical

* Robot is 2'x2'
* Each corner is a SDS MK4i unit with NEO motors and a CTRE CAN encoder
* * Drive motor is L2, which is 6.75:1
* * Angle motors have 150/7:1 gearing

## Motors

1. Front Left Drive. Positive power forward
2. Front Left Angle. 
4. Front Right Angle. Positive power counterclockwise
5. Front Right Angle. Positive power clockwise

## Angle motors

* The absolute encoder decreases as the angle motors are turned clockwise when viewed from the top
* With the bevel gears facing the right side, the angle encoders read correctly
* Flipping the wheels around also gives a ~180degree reading

