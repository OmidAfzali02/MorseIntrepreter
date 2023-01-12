# Morse Interpreter

This project is using Raspberry pi pico and Micro python.
With this Interpreter you can **encrypt messages** to morse code or **decrypt** them back.
 If you want to learn more about such projects and electronics you can checkout my github profile: 
 https://github.com/OmidAfzali02

## Thonny IDE

Since we're trying to have an interpreter instead of a program that we just click on run and some things happen, we need the Thonny IDE which offers the interpreter feature.
[Download Thonny](https://thonny.org/)

## Hardware

The model I created uses the following items:
 - Raspberry pi pico
 - any kind of buzzer or speaker
 - 2 LEDs (preferably different colors) I'm using Blue and Green
 - any kind of push button of push chassis
 - any kind of resistor (I'm using 1k)

## Diagram

With providing the necessary hardware now we need to connect them to each other. follow the Diagram.png file to make the proper connection.
![Morse Interpreter circuit diagram](https://github.com/OmidAfzali02/MorseIntrepreter/blob/main/Diagram.png)

# How to use
**1.** After downloading and installing Thonny IDE, Now you must connect your Raspberry pi pico to your OS and then Download and save [morse.py](https://github.com/OmidAfzali02/MorseIntrepreter/blob/main/morse.py) file on your Raspberry pi pico.

**2.** Click Run but nothing gonna happen.

**3.**  Although nothing happened but actually your interpreter is running and waiting you commands:

![How to Use](https://drive.google.com/file/d/1TF3lCO8xBN48AEpa0svMDVHHtOjENpiy/view?usp=share_link)

**4.** Now type command based on what you need to do.

## commands

 1. To Encrypt a message to Morse code use the following command:

  ``playmessage("hello world")``

Now checkout your LEDs and Buzzer you can see that they blink and make the morse code sound.
 2. To Decrypt a message use the following command:

 ``recordmessage()``
 
 After pressing enter you can use your push chassis to record the message; If you press the push chassis for a short time, the green LED will blink and it represents a short noise or `.` in morse code; And if you press the push chassis a bit longer, blue LED will blink and it represents a long noise or `-` in morse code. 

# How to reach me
.📫 [dev.omid02@gmail.com](mailto:dev.omid02@gmail.com)
 . [https://github.com/OmidAfzali02](https://github.com/OmidAfzali02)
