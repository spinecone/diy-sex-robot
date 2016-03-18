# Fun With Functions
Vibrators aren't very complicated machines. They're either vibrating or not vibrating. The things we can control are how fast they're vibrating, and the time between changing vibration speeds. The functions we will use today are:
* **analogWrite**(pinNumber, intensity)
    
    This is a function that arduino uses to set some pin to some number. The arduino has a set of pins that can be attached to different kinds of machinery. For example, if there were an LED bulb on pin number 1 that we wanted to set to 100 brightness, we would call analogWrite(1, 100). Since the pin number for the vibrator motor is 5, if we want to make the vibrator vibrate at 255 vibrations per second, we would call analogWrite(5, 255).
    
* **delay**(milliseconds)

  Delay is how we tell the arduino not to change anything. This isn't the same as doing nothing, however. If we tell the Arduino to vibrate at 255 vibrations per second and then tell it delay(30000), it will just keep vibrating at maximum intensity for 30 whole seconds (milliseconds / 1000 = seconds).



 

