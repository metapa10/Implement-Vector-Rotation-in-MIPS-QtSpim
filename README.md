# Vector Rotation in MIPS QtSpim

This repository contains an implementation of vector rotation using the MIPS assembly language in the QtSpim MIPS assembler and simulator. The project focuses on exploring two methods for computing vector rotation: complex multiplication and CORDIC (Coordinate Digital Rotation Computer).
Objective

## The primary objectives of this project are:

    Understand the features of the MIPS architecture and its instruction set architecture (ISA).
    Learn how to use the QtSPIM MIPS Assembler and Simulator.
    Gain experience in performing floating-point calculations and utilizing MIPS floating-point features.
    Compare and contrast the complex multiplication and CORDIC methods for computing vector rotation.

## Preparation

Before you begin, make sure to:

    Install and test the QtSpim MIPS assembler and simulator on your system.
    Review the preparatory materials in the course content related to floating-point operations, complex arithmetic, and CORDIC.

## Project Overview

The project involves rotating a complex vector a by an angle φ using two methods: complex multiplication and CORDIC. The vector a is always defined as a point on the unit circle with a magnitude of 1 (i.e., |a| = 1). The rotation angle φ is specified in degrees and can range from -90° to 90°.
Instructions

    Clone this repository to your local machine.
    Open the QtSpim MIPS assembler and simulator.
    Load the provided assembly program file.
    Run the simulation to observe the vector rotation using both complex multiplication and CORDIC methods.

## Memory Convention

Follow the provided memory convention for specifying the starting vector a and the rotation angle φ in the .data segment of your program. The look-up table values for Cartesian coordinates and CORDIC constants for 8 iterations should also be included in the .data segment.
Output

At the end of the program execution, the results of vector rotation using both methods will be displayed in the QtSpim Console. The output will include the rotated vectors computed through complex multiplication and CORDIC for the specified input vector a and rotation angle φ.

## Disclaimer

Please note that due to finite look-up table elements or CORDIC iterations, the computed results might have slight inaccuracies. These results, however, closely resemble each other and provide a valuable comparison between the two methods.
