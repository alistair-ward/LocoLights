# LocoLights

This is a simple Arduino project to control the lights on a miniature locomotive.

Target environment is VS Code with PlatformIO.

Target hardware is an Arduino Nano, with a I2C 16bit IO board, connected to SSR's which
switch LED lights.

The loco has a headlight, ditch lights, and "rear" (red) lights at each end. Which lights are 
turned on will depend on the direction switch in the loco.

Controlled lights (x2 for each end):
Headlight full
Headligh dipped
Ditch light left
Ditch light right
Rear lights.

Inputs:
Direction
Headlight full/dip

The ditch lights will flash alternately at a configurable rate (between 500 and 1000ms).

