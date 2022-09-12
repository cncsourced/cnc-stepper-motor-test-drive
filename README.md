# cnc-stepper-motor-test-drive

This is [CNCSourced] (https://www.cncsourced.com/) code from [this article] (https://www.cncsourced.com/cnc-machining/how-to-connect-stepper-motors-to-arduino-grbl-with-without-a-cnc-shield/)

This code accelerates your stepper motor to 300 RPM (for a standard 1.8° stepper motor). Then, the stepper motor runs at that speed for a short time, then it decelerates and stops. The stepper motor rests for 3 seconds and then moves in the opposite direction. This code repeats this process indefinitely.

You need to install Arduino IDE for free from here. Arduino IDE can flash the code into Arduino Uno but not Arduino Due.
