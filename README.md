# Piano Staircase → Gesture-Controlled Lightbar
## Overview



This project began as an attempt to build an interactive piano staircase using ultrasonic sensors and an MP3 module to trigger musical notes as users stepped on different stairs. Due to time and hardware constraints, the project pivoted into a gesture controlled RGB lightbar, which maps hand position to dynamic lighting effects.

The project documents both the original concept and the final working system, focusing on rapid prototyping, failure analysis, and iteration under real constraints.

Original Concept: Piano Staircase

The goal was to create a staircase where each step would:

Detect a user’s presence using ultrasonic sensors

Trigger a corresponding piano note via an MP3 module

Provide an engaging, interactive musical experience in a public space

Planned Features

Multiple ultrasonic sensors (one per stair)

MP3 module for audio playback

Microcontroller to handle sensor input and sound output

Real-time responsiveness for natural interaction

Challenges & Why It Didn’t Fully Work

While the concept was technically feasible, several constraints prevented full implementation:

Sensor interference: Multiple ultrasonic sensors caused cross-talk and unreliable distance readings when placed close together

Timing limitations: Managing simultaneous sensor inputs and audio playback exceeded the project timeline

Hardware complexity: Synchronizing multiple sensors with sound output required more calibration and shielding than anticipated

Time constraints: As this was a school-based project with a fixed deadline, there was insufficient time for deep iteration

Rather than submitting a non-functional system, I chose to pivot the project while preserving its core interaction idea.

Pivot: Gesture-Controlled RGB Lightbar

The project was re-designed into a lightbar that:

Uses ultrasonic distance sensing to track hand position

Maps distance values to RGB lighting patterns

Demonstrates real-time interaction and visual feedback

This pivot allowed me to:

Validate sensor input handling

Implement smooth mapping functions

Deliver a fully working interactive system

Final System Behavior

Hand distance is continuously read by an ultrasonic sensor

Distance values are mapped to:

Color changes

Brightness levels

The system responds instantly, creating a fluid interaction

Hardware Used

Microcontroller (Arduino)

Ultrasonic distance sensor

Addressable RGB LED strip

Power supply and wiring components

Software Overview

Language: C++ (Arduino)

Core logic:

Distance sampling and filtering

Mapping sensor values to RGB output

Non-blocking loop for real-time responsiveness

What I Learned

Designing for scalability matters early in hardware projects

Sensor interference can be a dominant constraint in physical systems

Pivoting is not failure — it’s a design decision

Working systems with clear interaction are more valuable than incomplete ambition

Future Improvements

If I were to revisit the piano staircase concept, I would:

Replace ultrasonic sensors with pressure sensors or IR break beams

Use better sensor isolation and shielding

Implement distributed microcontrollers per stair

Separate audio playback from sensor handling

Why This Project Matters

This project represents my first experience with:

Translating a large-scale interactive idea into hardware

Recognizing design limitations early

Making informed trade-offs under constraints

It directly influenced my later projects, which place stronger emphasis on robust interaction design and iteration.

📸 Media
