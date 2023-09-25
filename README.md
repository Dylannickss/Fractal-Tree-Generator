# Fractal-Tree-Generator
Code Overview

The Python script consists of the following functions:

tree(x: float, y: float) -> None
This function paints a tree starting from the specified (x, y) coordinates. It initializes the Turtle graphics, sets the trunk's length, and calls the branch function to create the tree's branches.

branch(angle: float, length: float) -> None
The branch function draws a tree branch at a given angle and length. It also recursively calls itself to create smaller branches until a specified length threshold is reached. The branching angle allows for the characteristic fractal appearance.

Interactive Mode

The program runs in interactive mode, allowing you to click anywhere in the Turtle graphics window to create new trees at different locations. This feature enables you to experiment with various fractal tree patterns.

Customization

You can customize the appearance of the fractal tree by adjusting parameters such as trunk_length and the branching angles in the code. Experiment with different values to create unique and captivating fractal patterns.

Enjoy exploring the world of fractals with this simple yet mesmerizing Python program!
