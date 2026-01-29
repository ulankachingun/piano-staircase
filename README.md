# Piano Staircase → Gesture-Controlled Lightbar
## Overview

This project began as an attempt to build an interactive piano staircase, where stepping on different stairs would trigger musical notes. The system was designed using ultrasonic sensors to detect position and an MP3 module to play corresponding sounds.

Due to time constraints and hardware limitations, the full staircase system could not be completed. The project was successfully pivoted into a gesture-controlled RGB lightbar, which uses ultrasonic sensing to map hand position to real-time lighting effects.

Date Started: March 28rd 2024

Date Finished: May 4th 2024

This project focused on rapid prototyping, physical interaction design, and making practical engineering decisions under real world constraints.

## Project Goal

The original objective was to design an interactive staircase that:

Detects user position using ultrasonic sensors

Triggers piano notes mapped to individual steps

Creates a playful, immersive musical experience

After pivoting, the revised goal became:

Demonstrate reliable ultrasonic distance sensing

Map continuous sensor input to real time visual feedback

Deliver a fully functional interactive system within the given time

## How It Works

The 8 ultrasonic sensor measures where the user’s hand is

The microcontroller processes distance data in real time

Distance and location values are mapped to RGB color and brightness changes

The LED strip responds instantly as the hand moves

This preserved the core interaction concept while simplifying the system architecture.

## Hardware Used

Arduino Uno and Mega

Ultrasonic distance sensor

Addressable RGB LED strip

Power supply and wiring components

Breadboard to connect all the compontents

## Software

Platform: Arduino

## Logic:

Continuous distance sampling

Value mapping for color and brightness output

Non-blocking loop for smooth responsiveness

# Note: The original staircase implementation involving multiple sensors and audio playback was not fully realized due to time and system complexity. This repository documents the working pivoted system and the design decisions behind it.

## Build Process

Initial system was designed around multiple ultrasonic sensors

Early testing revealed the ultrasonic sensor interference with the mp3 df module originally used

RGB lightbar was implemented to validate interaction design

## Challenges & Constraints

Ultrasonic sensor interference in close proximity

Ultrasonic sensor interference with the mp3 df module originally used

Limited time for multi-sensor calibration

Increased system complexity when combining sensing and audio

Need to deliver a functional system before the deadline

## What I Learned

System scalability should be considered early in hardware design

Simpler architectures are often more reliable under constraints

Pivoting can preserve core ideas while improving outcomes

Interaction quality matters more than feature count

## Future Improvements

If rebuilt today, I would:

Replace ultrasonic sensors with pressure or IR-based sensing

Use distributed controllers per stair for scalability

Separate sensing and audio playback subsystems

Revisit the full staircase implementation with more time

## Media

Combined demo video showing:

Original staircase concept testing

Final gesture-controlled RGB lightbar behavior



## Why This Project Matters

This project represents my first experience recognizing system limitations and making informed design trade-offs. The lessons learned directly influenced later projects that emphasize robustness, modularity, and interaction design.
