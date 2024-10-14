# lgpio-Servo
Uses the Libgpiod library to move a servo

This example will show how to control a servo, which is a fine-tuned motor which moves to a certain position and then rests. A servo has a motor and a sensor which moves to a certain position through a closed-loop system and are commonly used in robotics, steering for remote controls cars, and precise movement. Unlike a Direct Current motor which spins at many revolutions-per-minute (rpm), the servo motor usually move 180 degrees. A closed-loop servo usually has a pin on the inside of the servo motor casing to prevent it from rotating beyond 180 degrees. An open-loop servo allows the servo to move 360 degrees, although quite slowly, which is at a rate of 1 rpm. 

![](https://github.com/eugenedakin/lgpio-Servo/blob/main/ServoScreenGrab.png)


Install instructions are:
1) sudo apt install swig python-dev python3-dev
2) sudo apt install python-setuptools python3-setuptools
3) sudo apt install libunwind8
4) wget http://abyz.me.uk/lg/lg.zip
5) unzip lg.zip
6) cd lg
7) make
8) sudo make install
9) Open and compile the LibGPIODServo program and copy the program and libraries to the RaspberryPi Desktop
10) give the executable permission to run with something like: 'sudo chmod +x LibGPIODServo
11) run the program with something like: 'sudo ./LibGPIODServo


Here is the breadboard layout for the servo.
![](https://github.com/eugenedakin/lgpio-Servo/blob/main/ServoBreadboardFritzing-API2.png)
