# Remote-Control
ECE387 - Class Activity - Remote Control - Zhiyun Deng 

### Requirement need
- Arduino UNO $11  
- Servo motor $3.5
- Remote control, IR receiver,wires $5
- Total cost: $19.5

### introduce 
What I bulid is to control a servo motor with remote control. I use arduino UNO to control the servo motor to make the functionality I want, 
and use IR receiver to read IR signals from remote control. First, I download IRremote library for arduino from the internet.
Then open serial monitor 
and click two button of remote control to send a signal to IR receiver, the HEX code of whose two buttons appear in serial monitor, which are
using to control the servo motor,one for clockwise rotation and another for counter clockwise rotation.

### How it work
When push the FORWARD button, the motor will rotate clockwise, and push the BACKWARD button, the motor will rotate counter clockwise.
When push FORWARD or BACKWARD button twice, rotation will pause.
