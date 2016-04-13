# Fun With Integers

We're going to start with the simplest possible program: vibrating whenever power is supplied. An integer is any number that doesn't have a fraction or decimal, like 1, 2, or 3. They can be positive or negative, but today we're only going to be using positive integers.

### Setting up the Arduino IDE
* Download the version of the Arduino IDE (a text editor we'll be writing our programs in) that corresponds to your computer's operating system from https://www.arduino.cc/en/Main/Software.
* Once the IDE is installed, run it and check Tools -> Ports. There should be a checkmark next to "Arduino Uno." If there isn't, check the connections between your Shield, Arduino, vibrator, and computer.
* Copy the setup and loop from the previous chapter into a new Arduino file.

### Trying out some integers
* Change the analogWrite to a higher number so that it will vibrate.
* When you're ready to test, save your file and then click "upload." The program will run when you switch the vibrator's battery pack on.
* Try out a few different numbers to see what changes!

### If the vibrator doesn't work but your code looks right...
* Are all the vibrator and battery pack wires securely attached?
* Are the battery pack wires attached to the correct clips (black to "GND," red to "+V")?