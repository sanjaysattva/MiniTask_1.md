# project 1 : electronic weighing machine

The purpose of this project is to make a weighing machine to measure the weight of electronic components , thus callibrated in grams
the callibration can be reset after each measurement 

components used :
Hardware components

Arduino UNO	

Arduino UNO

3Kg Load Cell

Standard LCD - 16x2 White on Blue	

Adafruit Standard LCD - 16x2 White on Blue

I2C LCD Module

Software apps and online services

Arduino IDE	

comments : coding is part is critical

# project 2:Metal detector circuit

to make a simple metal detector using simple components and a LC loop

a copper loop with 140 turns is used . if the loop is near to a metal , current is induced in the loop , which results in an output from the proximity sensor 
and the buzzer is turned on.

Components Required



1 x TDA0161 Proximity Detector IC

2 x 47nF Capacitors (Ceramic Capacitor code 473)


1 x 1 KΩ Resistor (1/4 Watt)

1 x 330 Ω Resistor (1/4 Watt)

1 x 100 Ω Resistor (1/4 Watt)

1 x 5 KΩ Potentiometer

1 x 2N2222A (NPN Transistor)

1 x 5V Buzzer

Coil (copper wire of 26 – 30 AWG is taken and it is wound in to a coil of diamater 5 – 6 cm and 140 – 150 turns)

Additional Components (for LED)
1 x 220 Ω Resistor (1/4 Watt)
1 x 5mm LED

# project 3 : Car parking gaurd circuit using infrared sensor

The IR sensor will detect the obstacle with in 100cm, if there is any obstacle it will sense and give information

to the tone detector which will enable the LM555 timer to generate a PWM for the buzzer. The LM555 will generate the 

pulse which helps to buzz the buzzer so driver can understand that there is an obstacle.

the complete circuitry will be attached to the back bumper and placed at the center. The buzzer and led should be

placed on the dash board for visibility of light and hearing purpose for the driver.

components: 

IR sensor 

LM555 timer 

LM567 tone detector

Photo Darlington Transistor

LED

Piezzo buzzer


#profect 4: Smart Irrigation | Capacitive soil moisture sensor 

componentss

Wemos D1 mini Shields

Wemos SD shield

Wemos Relays shield

Jumper wires (generic)	

Jumper wires (generic)

Capactive soil moisture sensor

Wemos Triple base

Transformer

Seaflow350 pump

PVC pipes

USB-A to Mini-USB Cable	

USB-A to Mini-USB Cable

Software apps and online services:

Autodesk AutoCAD

Cura

Solidworks

Tinkercad

Lasercut

Makercase

Arduino IDE	

It is often noticed in many parks that most of the plants are not properly wet.In case of too wet 

water waste is high and consequently the cost of irrigation is high.To solve that we planned to make a device

that controls the irrigating system properly. So that there is no over watering and all plants

get the "required" amount of water.

wemos is able to control the pump in order to turn it on and off at the most suitable time, referring to the 

humidity of the soil in which the sensor is positioned.The system can be controlled via a telegram bot that allows us to know the humidity of the

soil when we request it,whether the pump is running or not.


# project 5: Rain alarm project

Rain water detector will detect the rain and make an alert; rain water detector is used in the irrigation field, home automation, communication, automobiles etc

If there is no rain, the resistance between the contacts will be very high as there will be no conduction between the wires in the sensor.
If there is rain, the water drops will fall on the rain sensor, which will form a conductive path between the wires and it also decreases
the resistance between the contacts.As a result, the wires on the sensor board will conduct and trigger the NE555 timer through the transistors circuitry.
Once NE555 is triggered, it will make the output pin high and which will make the buzzer to make alarm.

components:

Small Rain Sensor

555 Timer IC

BC548 NPN Transistor

2N2222 NPN Transistor

Bright White LED

1N4007 PN Junction Diode

Resistor (1/4 Watt)

Capacitor (Polarized)

10nF Ceramic Capacitor (Code – 103)

100pF Ceramic Capacitor (Code – 101)

Buzzer 




 # project 6:Internet Controlled RC Car with HD Video Using Raspberry Pi
 
 components

Raspberry Pi 4 Model B	

Flash Memory Card, MicroSD Card

16 GB+

Camera Module	

Raspberry Pi Camera Module

Or a USB webcam, or GoPro + HDMI capture card

Male/Female Jumper Wires	

Jumper wires (generic)	

2x6 Pin Header (5-pack)	

Digilent 2x6 Pin Header (5-pack)

Two 3-pin male-to-male headers


Software apps and online services

surrogate.tv

The range of the remote control car can be increased using the internet . We can also let anyone from any part of this world operate the car via the internet.
For this we dont need coding , but we have to use surrogate .tv
The ESC (electronic speed control)in the rc car is connected to the rasperry pi. We also use rasperry pi camera module and go pro to know the surroundings while operating the car.


# PROJECT 7: DIY Arduino Turn Signal Bicycle Safety Vest

Cars and motorbikes have an indicator . Why not we have one for bicycles. The light vest consists LED strips , which act as indicators. 
the led strips can be controlled by a remote or through a gyroscopic detector.
 
 Components:

Arduino Nano R3	

JLCPCB Customized PCB	

NeoPixel Ring: WS2812 5050 RGB LED	

Adafruit NeoPixel Ring: WS2812 5050 RGB LED

HC-05 Bluetooth Module	

Inertial Measurement Unit (IMU) (6 deg of freedom)	

Rechargeable Battery, 4.8 V	

Jumper wires (generic)	

Breadboard (generic)	

Pushbutton switch 12mm	

SparkFun Pushbutton switch 12mm

Software apps and online services

Arduino IDE	

LightVest is a light strip controlled by a microcontroller safely applied to a wearable fabric, such as a vest. the Bike Remote and the LED Bike Vest have two
Arduino (Microcontrollers) which communicate with each other through Bluetooth.
The LED vest works by using an Arduino to control a set of LED strips (WS2812B) based on the User’s action. 
When you turn the handlebar right the Gyroscope detects the relative change in orientation to the Right. The value ‘R’ (representing Right)
is sent to the LED Vest microcontroller via Bluetooth.The LED strip would light up the right arrows of the LED strip.

# PROJECT 8:IOT based Thermal Alarm
An IoT based thermal alarm system that goes off and sends SMS when it detects a thermal anomaly.

Hardware components:

Bolt WiFi Module	

Buzzer, Piezo	

5 mm LED: Red

LED, Blue	

Temperature Sensor

(LM35)

Software apps and online services

SMS Messaging API	

Twilio SMS Messaging API

the thermal sensor range is -55 celcius to 155 celcius.
This project requires coding knowledge in python.

# project 9:Roboticized Light Switch for Home Automation

 A roboticized cover which makes light switch a lot smarter.
 
  components:
  
ESP8266 ESP-12E	

Espressif ESP8266 ESP-12E

Push servo 20kg 180 degrees

Continuous rotation servo
	
10k ohm 0806 resistors
	
100nF 0806 capacitors
	
10uF SMD ECAP
	
100uF SMD ECAP
	
5.1mm female barrel jack
	
Push button 6.0x3.5mm
	
Rotary encoder
	
Rotary encoder knob
Needs to be cut down to 5mm height
	
5-6V 600mA power supply
	
Custom PCB. See step 3 for details


There will be three main components in this build:

1.Mechanical design

2.Control electronics for communicating with Home Assistant or any other MQTT server

3.Programming, to make the logic that automates and ties everything together

After building and configuring the project the lights can be controlled through four main ways:

1.Through a phone, tablet, computer or whatever you have that can access Home Assistant. I set it up as a local server so it will continue to work even if the internet is disconnected, which is important

2.Through voice with Google Assistant, which relays the commands to Home Assistant. This will only work when you have a valid internet connection

3.Through a rotary encoder with a built in push button. This would continue to work even if both internet was down and my local automation server stopped responding for some reason

4.The final way to control the lights is by manual override. As I can easily enough push or turn the light switch even with the upgrades installed
















