# Morse Reading Robot EV3

Autonomous LEGO EV3 robot developed to decode Morse code patterns from a printed track using colour sensing, timing analysis and real time robotic decision making.

## Overview

This project was developed for the Robotics and Autonomous Systems module.

The robot moves along a printed Morse code track and continuously detects transitions between red and white segments. Timing measurements are used to classify Morse symbols and convert them into readable text displayed directly on the EV3 screen.

The system combines sensing, movement control and autonomous decision making while operating in a real physical environment.

---

## Features

- LEGO EV3 autonomous robot
- Morse code decoding
- Colour sensor based detection
- Ultrasonic obstacle detection
- Real time timing analysis
- Dot and dash classification
- Character translation
- Dynamic environment interaction
- Physical robot implementation
- Demonstration video included

---

## Hardware Configuration

- EV3 Brick
- Two motors (Ports B and C)
- Colour sensor (Port 3)
- Ultrasonic sensor (Port 4)

---

## System Behaviour

The robot:

- Waits for centre button activation
- Moves continuously along the printed track
- Detects red and white transitions
- Measures timing duration
- Identifies dots and dashes
- Converts symbols into Morse characters
- Displays decoded text on screen
- Stops if an obstacle is detected

---

## Testing and Verification

Testing included:

- Colour transition detection
- Timing threshold verification
- Symbol spacing validation
- Full Morse sequence decoding
- Real world robot testing

The robot successfully decoded:

```text
RAS AT USW
```

during physical testing.

---

## Files Included

```text
Robot Last.lmsp
Robotics 2.pdf
Robot Demo.mov
```

---

## Academic Context

Developed for the Robotics and Autonomous Systems module as part of the BSc Computer Science programme at the University of South Wales.

---

## Author

Emad Ezzadeen  
BSc Computer Science Graduate  
University of South Wales
