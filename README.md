# Esploracontroluarm
Arduino Esplora acts as keyboard and sends commands to the uArmStudio client which controls the uArm Swift(Pro).

Esplora Controls uArm (Swift Pro via uArmStudio)

This sketch uses Esplora's keyboard emulation to control uArm Swfit Pro (4 DOF robot arm) via uArm Studio Control module.

The Esplora joysticks control x- and y- axes, up/down switch controls z-axis and left/right switch controls 4th motor (wrist) positions. Joystick button pushed down activates suction/gripper end effector, and covering light sensor resets the uArm to a default postion - if raw value goes below 250.

This is the first simple version to quickly try out my idea. Subsequent variations will include feedback of values to the Arduino TFT LCD.
