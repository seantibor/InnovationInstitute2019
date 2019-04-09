autoscale: false
slidenumbers: true
footer: ![inline 50%](photos/Innovation_Institute_white_transparent.png)<br>[Python Cheat Sheet - http://bit.ly/ParedesPython](http://bit.ly/ParedesPython)
text: #FFFFFF
background-color: #004712
header: text-scale(1.0), line-height(0.9), #FFFFFF, alignment(left)
list: bullet-character(•), line-height(0.6)


<!--
Micro:bits Presentation
Pine Crest School
Innovation Institute 2019
For use with DeckSet 2.0
-->

# [fit] Micro:bit Workshop
## Kelly Schuster-Paredes ([@KellyPared](https://twitter.com/KellyPared))
## Sean Tibor ([@smtibor](https://twitter.com/smtibor))

![](https://microbit.org/assets/posts/2016-11-21-TWSU-lego-challenge.jpg)

[.background-color: #000000]

---

# **Kelly Schuster-Paredes**
### Fort Lauderdale Middle School 
### Computer Science and Education Technology Specialist

[@KellyPared](https://twitter.com/KellyPared) on Twitter

```python
kelly_fun_facts = {'origin': 'Sebastian, Florida',
                  'countries_taught_in': ['Peru', 'USA', 'UK']}
```

![left](photos/kelly.jpg)

[.header: alignment(left)]

---

# **Sean Tibor**
### Fort Lauderdale Middle School 
### Computer Science and Education Technology Specialist

[@smtibor](https://twitter.com/smtibor) on Twitter

```python
sean_fun_facts = {'origin': 'Anchorage, Alaska',
                  'can_sew': True}
```
![right](photos/Sean Hi Res Photo.jpg)

[.header: alignment(left)]

---

Co-hosts of the [*Teaching Python*](https://www.teachingpython.fm) podcast
(for good-looking and talented people like you)

```python
while shameless_plug:
    audience.listen_to(podcast='www.teachingpython.fm')
```

![right fit](photos/teaching_python.jpg)

---

# [fit] Micro:bit Workshop
## Minimize talking, maximizing doing

[.header: alignment(center)]

---

# [fit] What is the BBC micro:bit?

^ Fastest growing programming language
^ "Full Spectrum" Language
^ Emphasizes readability

![original inline](https://microbit.org/images/microbit-hardware-access.jpg)

[.header: #004712]
[.background-color: #FFFFFF]

--- 

# Micro:bit Coding Languages & Coaches

- Make:code (Pedro)
- MicroPython (Kelly)
- C (Good Luck & Godspeed!)

Sean will float around.

---

# MakeCode Hello World

![inline](photos/makecode_hello_world.png)

[.background-color: #FFFFFF]
[.header: #004712]

---

# MicroPython Hello World

```python
from microbit import *

display.scroll('Hello World')
```

---

# Beginner Micro:bit Challenges

- Push a button, show an image
- Hook up a Pimoroni Speaker
- Knight Rider LEDs

---

# Intermediate Micro:bit Challenges

- Shake the Micro:bit, play a song
- Plot light level data with Mu
- Make a Rock, Paper, Scissors Game
- Micro:bit Fireflies

---

# How to Flash an External LED on a Microbit
## By Olivia M.

---

First, gather the materials. You will need:

- banana clip to alligator clip wire (x2)
- external LED
- Microbit
- Micro USB cord

![](photos/external_led/image5.png)
![](photos/external_led/image4.png)
![](photos/external_led/image2.png)
![](photos/external_led/image1.png)


[.background-color: #000000]

---

# Instructions

---

## Code:
First, open Mu Editor and start a new code.  Then, type this code:

```python
from microbit import *

while True:
    pin0.write_digital(1)
    sleep(500)
    pin0.write_digital(0)
    sleep(500)
```

---

Line 1: importing microbit library into the code
Line 3: starting a forever loop (making the code under run forever)
Line 4: pin0 (0 hole on microbit) blinking for 1 second
Line 5/7: stopping pin0 for 500 milliseconds
Line 6: turning pin0 off (allowing it to blink)

---

## Building the Microbit Part:

1. Plug in micro USB cord into the USB in your computer
1. Plug the Micro USB end into the Microbit
1. Plug the banana clip ends of the alligator to banana clip cords into the 0 and GND holes in the microbit
1. Attach the alligator ends of the alligator to banana clip cords to the 2 metal ends of the external LED (one alligator clip on each wire end) 
1. Run the code (make sure Mu is on Microbit mode)

---

## Congratulations, you have now made a flashing external light using a Microbit and Python 3!

---

## If you need more help:
- [https://www.youtube.com/watch?v=0P7P4DpVlZw](https://www.youtube.com/watch?v=0P7P4DpVlZw)

- [https://learn.adafruit.com/micro-bit-lesson-2-controlling-leds-on-breadboard?view=all](https://learn.adafruit.com/micro-bit-lesson-2-controlling-leds-on-breadboard?view=all)


---

# [fit] Get Going!

---

# Next Steps

- Get some clips and sensors
- Make a piano with the accessories
- Build a robot or R/C car
- Follow us on Twitter
- Listen to our Podcast ([teachingpython.fm](https://www.teachingpython.fm))

---

# Clone our [GitHub Repository](https://github.com/seantibor/InnovationInstitute2019)

[https://github.com/seantibor/InnovationInstitute2019](https://github.com/seantibor/InnovationInstitute2019)

---

# Thank You