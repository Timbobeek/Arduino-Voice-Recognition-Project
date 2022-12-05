# Arduino-Voice-Recognition-Project
A plan of what I need to do.

In general: I want to build a robot that moves a leg on a chosen voice command.\

DONE-I need to look at what tools I have available for the speech recognizer\
-Find out what each piece is responsible for, why it exists, how it works (and if it is compatible with my project idea)\
DONE-See if I can set up a specific word to be recognized OR if it only works with a general voice sound\
DONE-Figure out how to connect the speech recognizer with Arduino NANO directly
-Figure out how to physically connect Arduino Nano + Motor leg + Voice Recognizer to make it work\
    (with that, I need to learn to understand why the wires are connected the way they are)\
-Look up examples of code to make such a mechanism move the leg by default automatically once something is said to the voice recognizer\
  (and again, understand what each line of code stands for)\
  
  
  At the end, I was able to connect Tower Pro sg92r motor + Arduino Nano + Grove Speech Recognizer using wires and a breadboard. For this demo, the motor engine moves one way when I say "Start" and the other way when I say "Stop". The code also prints the number of each voice command in the serial monitor along with the command itself for better tracking.
  
  Video Demo of the main project complete:
  
  

https://user-images.githubusercontent.com/68671029/205173271-86664910-19fa-47bb-9952-3222ec630d42.mp4


  
  
 Additional?\
 
 -Maybe see if I can make the mechanism do other things, such as light a built-in bulb blink\
 -Attach multiple legs and make a robot move on voice (Arduino-Voice-Recognition-Project 2.0)!
