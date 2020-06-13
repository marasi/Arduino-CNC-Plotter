Arduino Plotter

First of all, I am a highschool teacher, and I like to use technology in class with my students, eventually teaching some, such as coding or robotics.
My Final Project has the goal to apply all knowledge from CS50, creating a GUI software to control an Arduino device that controls a Plotter.
The plotter itself is another project of my own. It was build with e-waste.

To understand better, I will make my point in three ways:
1- To build a machine, named Plotter, with computers waste parts.
2- To use an Arduino as interface to control the plotter itself.
3- To create a piece of software that read PLT files and execute commands into Arduino, than print the file.
 
About the software:

The Plotter software was created using Microsoft Visual Code, Visual C#.
It read PLT files (Vector-based plotter file created by AutoCAD drawing software; can be printed using a plotter, which prints images using lines instead of dots; based on the .HPGL format.). The files contains coordinates X and Y of an drawing.
The coordinates are cached and sended to Arduino.
Arduino interprets the X Y coordinates and moves the stepmotors to specific spot.
Z axis is corresponding to a pen. When Z is setted the Pen goes up or goes down, drawing points and lines.
The software was first design by eziosoft, who lead me the first steps to finish my project. I was helped by André Breier when debugging the code.
There are few bugs, but the basic functionality is complete.


