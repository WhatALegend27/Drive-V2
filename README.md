# Drive-V2
A secondary drive function for the VEX Clawbot that adds adaptive speed (speed changes depending on how hard you press on the joystick) and fixes some bugs

This program is meant to act as a replacement of the default Drive function built into the VEX Clawbot. If you are having problems with the program working (i.e. claw will not close, arm won't lower), download this program onto your VEX Clawbot and run the program.

NOTE: If you run the drive function instead of the program named Drive V2, IT WILL NOT WORK.

Configuration:
- Left Motor: Slot 1
- Right Motor: Slot 10
- Claw Motor: Slot 3
- Arm Motor: Slot 8
- Front Bumper Button: Slot A
- Rear Bumper Button: Slot B
- Range Finder Rear: Slots C and D

Controls:
- Move Forward: Left Stick, forward
- Move Backward: Left Stick, reverse
- Turn Left: Right Stick, left
- Turn Right: Right Stick, right
- Close Claw: R1 (Inner Right Bumper)
- Open Claw: R2 (Outer Right Bumper)
- Lower Arm: L1 (Inner Left Bumper)
- Raise Arm: L2 (Inner Right Bumper)
- Stop Program: Press Buttons on Clawbot or 'B' on Controller

This configuration is the standard configuration for the VEX Clawbots. Most of your robots should have this configuration.

Note that the buttons and range finders are not required for the program to function. The buttons act as emergency stop buttons and the range finder does nothing.

Also, if you would like to change the velocity of the Claw Motor, Arm Motor, or the Drive Motors, change the ClawMotorVelocity, the ArmMotorVelocity, or the MotorVelocity variables respectively. You can find them at the top of the "when started" block. The ClawMotorVelocity and ArmMotorVelocity variables accept valuesfrom 0 - 100 and the MotorVelocity variable accepts values from 0-1 
