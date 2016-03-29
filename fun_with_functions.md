# Fun With Functions
Vibrators aren't very complicated machines. They're either vibrating or not vibrating. The things we can control are how fast they're vibrating, and the time between changing vibration speeds. The functions we will use today are:
* **analogWrite**(pinNumber, intensity)
    
    This is a function that Arduino uses to set some pin to some number. The arduino has a set of pins that can be attached to different kinds of machinery. For example, if there were an LED bulb on pin number 1 that we wanted to set to 100 brightness, we would call analogWrite(1, 100). Since the pin number for the vibrator motor is 5, if we want to make the vibrator vibrate at 255 vibrations per second (the highest setting), we would call analogWrite(5, 255).
 
* **delay**(milliseconds)

  Delay is how we tell the arduino not to change anything. This isn't the same as doing nothing, however. If we tell the Arduino to vibrate at 255 vibrations per second and then tell it delay(30000), it will just keep vibrating at maximum intensity for 30 whole seconds (milliseconds / 1000 = seconds).

* **pinMode**(pinNumber, intensity)

  We won't be messing around with this function very much, but it's an essential one. This tells the Arduino what we want to do with the machinery attached to the pin at pinNumber. For our vibrators, this will always be OUTPUT, so we'll be calling pinMode(5, OUTPUT) at the beginning of every program. However, different kinds of devices like buttons or switches can be used as INPUT.
 


###   That's it! Everything else is up to your imagination.


To improve on our program from the last chapter, let's make it vibrate for 2 seconds, then pause for 2 seconds. Remember that 1000 milliseconds is equal to 1 second, and that the delay() function will continue running the previous function while delaying.



