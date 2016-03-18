# Fun With Functions
Vibrators aren't very complicated machines. They're either vibrating or not vibrating. The things we can control are how fast they're vibrating, and the time between changing vibration speeds. The functions we will use today are:
* **analogWrite**(pinNumber, intensity)
    
    This is a function that arduino uses to set some pin to some number. The arduino has a full set of pins that can be attached to different kinds of machinery. For example, if there were an LED bulb on pin number 1 that we wanted to set to 100 brightness, we would call analogWrite(1, 100). Since the pin number for the vibrator motor is 5, if we want to make the vibrator vibrate at 255 vibrations per second, we would call analogWrite(5, 255).



 

