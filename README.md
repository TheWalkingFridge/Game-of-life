# Game-of-life

## Introduction
This is Conway's version of Game of life. Made as an assignment for Concurrent Computing.  
The simulation is designed to work on xCORE-200 eXplorerKIT.

## Functionality
The simulation is written in XC.  
There are 6 available boards - 16x16, 64x64, 128x128, 512x512 and 1024x1024.  
Upon button press, the program will distribute the the board within 4 or 8 "workers" working on  
different threads.
It includes:
* Button Listener 
* Orientation Listener
* LED trigger
* Synchronised thread communication using channels

## Examples
Board: 64x64, 100 Iterations, Time taken:2315 miliseconds  
<img src="Images/64x64.png" height="256" width="256"> <img src="Images/64out.png" height="64" width="64">