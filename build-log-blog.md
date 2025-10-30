10-30 | V . 1 . 0 . 0
---------------------
  Hello, and welcome to the documentation of my cyberdeck. In this commit, I want to go over all of the materials involved with the project currently, as well as ouline objectives and ideas.

  In my view, all cyberdecks should have the goal of being a one-stop-shop for any specific task they are designed to carry out. For example, you don't want to build a deck only to have it be a less efficient and stable version of your current framework, that wouldn't make sense. Therefore, my main goal for this project is to create something that I find byself able to use on a daily basis.
  Beyond this, there is a few other things I want to consider. I am relatively new to the RPi, and familiarity with that is important. I do have a background in VEX robotics, so I also want to gain some more experience in physical hardware by utilizing different sensors that I have around. These consist of:

**Sensors:**
    1. Raindrops Sensor
    2. Sound Sensor
    3. PIR Sensor
    4. Gas Sensor
    5. Temp & Humidity Sensor

**Displays, Screens, and Lights:**
    1. LCD 1602 Module (Micro LCD Screen)
    2. LED Bar Graph
    3. LED Matrix
    4. 4 digit and 1 digit 7-Segment Display

**Other:**
    1. RC522 RFID Module
    2. Rotary Encoder
    3. Real-Time Clock
    4. Membrne Switchpad
    5. Various Buttons and LEDs

  I may use all or just some of these sensors, but I list them as a log of what is availiable to me. This list isn't fully exhaustive, but it serves as a good starting point. As I continue, I may add on to this material list. 

  The first thing I wanted to begin working on is the exterior of the case. The case is likely to be 3D printed, but I prefer to choose what I want it to have before I begin to design around that. 
  
  The main things I want to include are:
    1. An LED Matrix to use scrolling text as well as animations
    2. A Rotary Encoder connected to a motor as the lock
    3. LED Lights to serve as the confirmation indicator for passcodes, status, and and anything else

  Beginning with the LED matrix, I wanted to begin with five animations.
    1. A Circle moving inwards to signify shutting down
    2. A circle moving outwards to signify powering on
    3. A "Welcome CodedArrow" Message to scroll across when the combination is inputted correctly
    4. An "Access Denied" Message for when the password is inputted incorrectly
    5. An idle animation for active use

  I began in Scratch, which is an easy way for me to throw out design ideas without too much hassle/backend code. If I like the idea, I can easily move over to a text language.

  Here is an example of the animations. Each square represents a dot in the matrix (8x8)
  
![LedMatrixIn](https://github.com/user-attachments/assets/2864634a-1c71-413b-9f40-0383a202e8c0)

![LedMatrixOut](https://github.com/user-attachments/assets/145e3680-9765-457d-aa6e-8a9ae2fae50f)

![LedMatrixCARROW](https://github.com/user-attachments/assets/e4522919-20f4-40d9-a0bb-7ffc868b3749)

![LedMatrixDENIED](https://github.com/user-attachments/assets/4dcf1082-89bc-4dcb-a157-6fb8bda47230)

![LedMatrixIDLE](https://github.com/user-attachments/assets/5f776fdf-9b87-40f7-916b-2aa21650daa2)

  
