# Flandre Scarlet Music Box

A small DIY music box project inspired by Flandre Scarlet from Touhou Project.
The project is designed to play a simplified, single-note version of U.N. Owen Was Her? using a microcontroller, buzzer/speaker, and LEDs.

# Goals 

- Learn the basics of Arduino and embedded programming
- Experiment with playing musical notes electronically
- Convert MIDI music into a format suitable for a microcontroller
- Build a physical music box using a breadboard first, then a permanent perfboard design
- Create Flandre-inspired LED wings for the final enclosure

# Hardware

- Arduino
- Passive buzzer or speaker
- LEDs
- Resistor
- Push button
- Battery/any power source
- Breadboard
- Jumper Wires
- Perfboard
- enclosuer for the project

#  Status

Currently: Learning and prototyping.

This is my first Arduino/electronics project, so the design will evolve as I learn more about embedded programming and electronics.

AI tools were used during development to help with C++ code, MIDI processing, debugging, and learning unfamiliar concepts.
The project is also a learning exercise for me as a BSIT student and my first experience working with Arduino/electronics. I tested, modified, and iterated on the generated code while learning how each part works.
The goal of this project is not to claim that all of the code was written from scratch, but to use AI as a learning and development tool while building something I genuinely wanted to make.

# Music

The project is based on "U.N. Owen Was Her?", the Extra Stage boss theme associated with Flandre Scarlet in Touhou 6: Embodiment of Scarlet Devil.

This is a fan-made learning project and is not affiliated with the Touhou Project.

# How to run the code

Just do
- g++ melody.c++ -o melody -lwinmm
- .\melody
