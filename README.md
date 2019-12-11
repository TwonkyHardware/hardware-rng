# hardware-rng
Control and processing software for a simple hardware random number generator

This project involves the construction of a hardware random number generator using avalanche 
noise produced by a reverse-biased diode.  This repository will contain microcontroller software
for the circuit as well as a set of programs to analyze the results for randomness.

* Microcontroller Python code to sample noise from the circuit and output the results as binary values
* 'Static' randomness test: a program to display the received data as a grid of black and white pixels akin to analog-signal TV static for a quick visual check of randomness
* 'Circle' randomness test: convert the received data into points in a unit square.  Assuming random distribution, calculate the value of pi by counting how many points fall into a unit circle.  The accuracy of the result is a check of the randomness of the input data.
