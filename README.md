Moodlight User Manual
==================

---> Cover\\
---> TOC

Getting started
---------------
###Quick start Guide
* Connect the power plug to your wall outlet.
* Install the Moodlight app to your Android smart phone. 
* Connect the Moodlight via Bluetooth in the general settings section of the Android phone.
* Control the Moodlight via app.
* Enjoy the unique star projection. 


(Hardware installation guide)
-----------------------------
The Moodlight comes plug and playable out of the Box. The only additional connection that needs to be made is to plug the powercable into a wall socket. 
As soon as the power cable is connected the lamp will quickly blink (TODO how many times and which color) to indicate that everything is connected properly. 


### Troubleshooting 
Some problems which might occure and a possible solution: 

- The Wall plug is connected properly but the Moodlight does not power up.
  1. Check the connection between the cable and the 2.1mm Barrel Plug is the connection solid. 
  2. Make sure that the Arrow with the Plus sign is pointing to the CEN mark on the cable. 
  3. Check the connection between the cable and the 2.1mm socket on the power socket on the controller board.

- Star projector dome is not turning
  1. Check the connection of the Black and Red cable coming from the motor and the screw terminals on the controller board. 
  2. Try to run the motor without the dome. If it works then the dom might be too tightly screewed down. 
- Wrong color assignement.
  1. Check the screew terminals and the cables comming from the star power led and assign them correctly if necessary. 
- Bluetooth does not work. 
  1. Check the Bluetooth power jumper. It needs to be plugged in to have a power connection between the Voltage Regulator and Bluetoot module. 
  


uC user interface
-----------------


Installation of Android app
---------------------------


Pairing with smartphone
-----------------------


Android user interface
----------------------
The Android Moodlight App is devided into three tabs: RGB+W, HSV and Service. 

Open the Moodlight controller application "The Dome" by clicking on the corresponding Icon on the home screen of the smartphone. 

How to use the app with the different tabs:
### RBG+W 
Within the RGB+W tab the red, green, blue and white values are directly controllable. The values can be entered with four independent horizontal sliders. Move any of the four sliders from left to right to increase the brightness of its represented color. 

The horizontal Motor Sllider below the RGBW sliders allows to controll the Motor speed directly. Move the Slider from left to right to increase the rotation rate of the Star dome. 

On the bottom is Coq-wheel turning when ever new data is sent to the Moodlight this sent to the Moodlight. The Button on the Right of the Coq-wheel allows to toggle the Light on and off and is also indicating the color that has been set for the light. 


### HSV 
Within the HSV tab the three parameters for Hue, Saturation and Value can be set by sliding the three sliders horizonaly. The actual representation of what the current slider possition means is represented as a strip behind the slider. Just below the three sliders are the calculated RGB values. 

There is the option to include the white LED or leave it out. The option is represented by a rectangular checkbox. Checking the box includes the white led leave the box empty to not use the white led. 

The color field on the bottom shows a preview of the set color. It changes as soon as one of the three slider changes. 

### Service
The service tab is used to connect and disconnect to the Moodlight. It can also be used to synchronize data and use the send this: section to send commands directly. This can help to find problems and or check additional functionalitites. The data received from the moodlight is also written into the text field on the bottom of the Service tab. 

### App general
Any additional informations and messages are displayed as little pop ups on the bottom of the application screen. There is one popup for showing that there is no Moodlight connected. 
(TODO are there more?)




(Web user interface)
----------------------






