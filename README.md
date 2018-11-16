# Temperature-Humidity-Rain-detecting-system
### Introduction:
A brief explanation on how you obtain the values from the atmosphere using sensors and how we constantly monitor the values using Thingspeak. So, mainly we focus on the values of temperature, humidity. Along with this we have made a system which detects the rainfall.

### Main Motto:
Now a days were are facing many problems due to high temperature and humidity conditions, as we don't know the exact temperature reading we may perform actions which may result in fail. So our main motto is to serve the purpose of live mointoring values of temperature and humidity, So that we can overcome the problems(mainly industry purpose).

###  Uses:
For manufacturing highly sophisticated integrated circuits in semiconductor industry, humidity or temperature levels are constantly monitored in Industries.In some of domestic applications, such as intelligent control ofthe living environment in buildings, cooking control for microwave ovens, and intelligent control of laundry etc

### Description:
Our project detects the temperature and humidity from the atmosphere(current) using DHT11 sensor.DHT11 is a basic, ultra low-cost digital temperature and humidity sensor. It uses a capacitive humidity sensor and a thermistor to measure the surrounding air, and spits out a digital signal on the data pin. We take the values from the sensor and pass to code which was loaded into ESP8266. And shows or displays the values in Serial mointor where we run or upload the code into ESP8266. From thier we use a API key to send the data to Thingspeak, where we update the values for every 15 seconds. Along with this we had designed Rain Detecting System if rains falls, it shows the rain is detected otherwise it shows rain not detected.

### Components:
1. DTH11 Humidity and Temperature Sensor
2. ESP8266(NodeMCU)
3. Rain Module Sensor(Rain sensor)
4. BreadBoard
5. Thingspeak
6. DHT Library
7. Connecting wires 

### Working Principle:
So the main working principle of ESP8266 is The ESP8266 can be controlled from your local Wi-Fi network or from the internet (after port forwarding). The ESP-01 module has GPIO pins that can be programmed to turn an LED or a relay ON/OFF through the internet, so here we connect DHT and ESP8266. DHT11 Sensor Module is connected to digital pin 12 of Arduino. Wi-Fi module ESP8266’s Vcc and GND pins are directly connected to 3.3V and GND of Arduino and CH_PD is also connected with 3.3V. Tx and Rx pins of ESP8266 are directly connected to pin 2 and 3 of Arduino. Software Serial Library is also used here to allow serial communication on pin 2 and 3 of Arduino.

### Team Members:
1. Mounika Smitha Kallepalli-AM.EN.U4CSE16230
2. Harika Kothuri-AM.EN.U4CSE16035
3. Padmavathi Patnala-AM.EN.U4CSE16047
4. Lavanya Undela-AM.EN.U4CSE16064

### Individual Contributions:
1.U4CSE16230(Mounika)- Worked on DHT11 humidity and temperature interfacing, getting the libraries and fixing the flaws in the system and observed how the sensor detects the values from atmosphere(using thermistor and detecting digital pin), connected circuit ESP8266 along with the sensor(Temperature and humidity detecting).
2.U4CSE16035(Harika) - Worked on Thingspeak server and learned how to take the values from ESP826 and display as a graph in Thingspeak website using API's and connected circuit ESP8266 along with the sensor(Temperature and humidity detecting).
3.U4CSE16047(Padmavathi) - Worked on Rain module interfacing, connecting the rain module sensor to ESP8266, fixing flaws in the system, observed how the rain module sensor works, connected circuit ESP8266 along with the sensor(Rain detecting).
4. U4CSE16064(Lavanya) - Worked on Client Server Model of the system, tried to implement but has few flaws, worked on the working priciple of the Temperature and humidity and Rain detecting system and worked on the flaws in the whole system. 

