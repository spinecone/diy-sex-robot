# Fun With Conditionals and Control Structures
**Conditionals** are statements that return either **true** or **false**. For example, the conditional statement 100 > 70 evaluates as **true**, whereas 0 < 300 is **false**. 

Some different kinds of conditional statements we can make are:
* x **<** y (x is less than y)
* x **>** y (x is greater than y)
* x **==** y (x is equal to y)


**Control structures** use conditionals to make choices within code. One type of control structure is **if** and **else** statements.






For loops, another type of control structure, allow us to make a set number of repetitions. They're made up of 3 parts: initializing a counter, checking the counter in a conditional, and updating the counter. When the conditional statement becomes "false", the for loop will stop running.
<br> <img src="for_loop.png"><br>
In this program, we're increasing the intensity of the vibration over the course of 10 seconds, at a maximum of 200 intensity before repeating the loop. Our counter, x, starts at 0, repeats the for loop until it reaches 10, and increases by 1 at every repeat (x++ is another way of saying x = x + 1).

* Copy the program shown above and test it out on your vibrator.
* Right now the program starts at 0 intensity and increases to 200 intensity. How would we make it start at 200 intensity and gradually fade to 0 intensity?




* Hmm, this program might be too intense. How can we add a 2000 millisecond pause whenever the vibration speed is at 0?
* The pause is nice, but it would also be good for the highest speed vibration to last longer. How can we make the program vibrate at the highest speed for 3000 milliseconds before fading out?
* Let's make the program more interesting. How can we make the fade in faster than the fade out?

