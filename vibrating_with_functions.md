# Vibrating With Functions
We're going to start with the simplest possible function: vibrating whenever power is supplied.
* Open up a new file in Arduino
* In setup(), set pin 5 to be the output
* In loop(), set the speed of pin 5 to a high enough intensity that you can detect it.
* That's it! Save, click "upload," and turn on your battery pack to test your function.
* Try to find the lowest intensity that the vibrator will work with.

Next, we'll use delays to vibrate for 1 second, then pause for 1 second in a cycle. Remember that 1000 milliseconds is equal to 1 second, and that