# Arduino101_BLE_Blynk_AdafruitMotorV2
Code for a BLE rover using Blynk as the remote and Arduino 101 with Adafruit motor shield.

Instructions:
As sharing Blynk apps is in beta right now for android and I am in the iPhone camp I can't share the Blynk app right now. 

Steps.
Install the Blynk App on your phone.
  Create a new project
  Drag four buttons, a slider, and the BLE module on your app.
  Edit the Slider to be a value from 0 to 255 and have it write to V0 (this is the motor speed)
  Edit the buttons and have them write a one momentarily to V1 through 4 (this are for the motors forward and backward commands)
  
Copy the Blynk auth token into the Arduino sketch in the proper place in line 18
Load the sketch into your Arduino 101

From your phone disconnect or delete all BLE connections, they can interfere with communication.
In the Blynk app click on the bluetooth connection block and connect to the Arduino.
Put the Blynk app into run mode and mash the buttons!

Full tutorial can be found here along with videos.

http://www.electronhacks.com/2016/12/intel-arduino-101-ble-blynk-tank/

https://www.hackster.io/fileark/intel-arduino-101-ble-blynk-tank-57812d
