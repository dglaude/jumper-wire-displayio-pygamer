# jumper-wire-displayio-pygamer
A port of the Jumper Wire game to displayio on the Adafruit PyGamer

This branch is a project to run the game on Adafruit PyPortal...

But the Adafruit PyPortal does not have joystick build in so some alternative are require.
1) I want to use the Bluepad32 project that offer support for various wireless joystick by using the Bluepad32 firmware on the AirLift ESP32, it then work with WiiMote
2) Another way to have a joystick connected to the PyPortal is to use the I2C connector (you first need to solder for 3V usage) you can then attach a Classical Controler and attach it to the I2C bus
3) It should be possible to use the touch screen of the PyPortal to have keys for some defined location of the screen

My particular interest i in Bluepad32, but I might revisit alternative too.

Thank you to deshipu for providing the base game for those experiment.
