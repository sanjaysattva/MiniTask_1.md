 # DIY Arduino Turn Signal Bicycle Safety Vest

**The problem statement :**
To make a safety vest for cycle riders , containing light strips , to act as an indicator . 

**Ideation and planning:**
Components used are :
Arduino Nano R3	(two ),
JLCPCB Customized PCB	,
Adafruit NeoPixel Ring: WS2812 5050 RGB LED,
HC-05 Bluetooth Module,
Inertial Measurement Unit (IMU) (6 deg of freedom),	
Rechargeable Battery, 4.8 V	,
Jumper wires (generic)	,
Breadboard (generic)	,
SparkFun Pushbutton switch 12mm.


The light  strips form a diamond at the back of the vest and two strips at the shoulder. Arrows indicate the direction in which the cyclr is going to turn , just like indicators in cars. 

The light strips are controlled in two ways :

1. Via a remote 

2. Via a gyroscope at the handle bar to detect the direction at which the cycle is turning.

![lightvest-first-prototype](https://user-images.githubusercontent.com/85502194/122208703-406fa280-cec1-11eb-83b3-056f80df3dbb.jpg)

Some things that we must sure of are the durability of the batteries and the their size . The batteries have to withstand sudden physical impacts in case of accidents. Also they must weigh less and be compact.  Li on RC battery pack was used as the  best alternative , but size was compromised a bit here.
Also , the LED strips must be removable from the vest , so that vest is cleanable . Also the even if a single LED is faulty , the entire strip wont work.

**Pipeline:**

 The remote and the LED Bike Vest have two Arduino Microcontrollers which communicate with each other through Bluetooth. The LED vest works by using an Arduino to control a set of LED strips (WS2812B) based on the user’s action. For say pressing the right arrow button will send a signal via bluetooth to the microcontroller , which results in the LED strips lighting up the right arrow. 
 
 However. we cant click the rempte every time we turn . This is where the gyroscope comes into play . When the handle bar is turned , the signal is sent via bluetooth to the microcontroller.
 
 **Prototyping phase:**
 
 The apparatus and the LED strips can be attached to the vest using velcros, the best way to easily remove when needed. We can even have a mount on the handlebar to have the on/off switch for the LED strips. We cant test the vest on rainy days unless we made sure that it is 100 percent weather proof. 



