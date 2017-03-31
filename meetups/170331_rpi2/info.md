### Nelson 
_Raspberry Pi wizzard_

Nelson Zhang is an engineer specializing in embedded architecture and circuit design, manufacturing, and taking products to market. He has previously worked at Amazon, Xinchejian, and Leap Motion, and for the past 3 years has served as cofounder and CEO of a smart bluetooth headphone startup. Before dropping out of UC Berkeley to take the Thiel Fellowship, he also founded Hackers@Berkeley and ran various hackathons, workshops, and industry talks. He spends his free time on indie films, electric guitar, and metalworking.

### Practical Hacking with Raspberry Pi

The Raspberry Pi 3B has a full GPIO digital pin interface, including SPI and I2C ports. This allows for various digital input and output devices like sensors, motors, etc. to be interfaced with RPi and controlled from the Linux environment. We will learn to set up and use the software and hardware necessary for sensors such as the Raspberry Pi Sense HAT (temperature/pressure/humidity + inertial measurement unit).

Since the RPi does not have it’s own analog ports, we will also learn to use an Arduino to interface with analog sensors/actuators while passing data back and forth to the RPi using a USB or UART serial connection. This requires writing C code for the Arduino, while setting up a serial connection on the RPi using any language with system calls e.g. Python.

After this workshop you will have the knowledge and skills to help you build any IoT project with the RPi.

Agenda

• 30mins introduction to RPi, Sense HAT, Arduino, and sensors/actuators

• 30mins software set up on RPi and laptops

       • Install Raspbian, set up Python and sensor libraries on RPi

       • Install Arduino IDE, set up ssh and sensor libraries on laptop

• 30mins hardware assembly

      • Attach SenseHAT and casing

      • Hook up other digital sensors

      • Connect Arduino over USB or UART

      • Hook up remaining sensors to Arduino

      • Explain basic relevant digital electronics concepts (power/ground, digital vs analog, SPI/I2C/UART protocols)

 • 30mins coding and testing

      • Write and run SenseHAT code

      • Write and flash Arduino sensor + serial code

      • Write and run Python serial code

      • Output real-time feed of sensor data

Requirements：

Bring your own laptop with Windows, OS X, or Ubuntu. Preferably have Arduino IDE already installed. If on Windows, please install an ssh client such as PuTTY, Cygwin, Powershell, etc.

Install software download link.
