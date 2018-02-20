# BuildABot
Motive: To increase interest of kids in STEM branch.
It has 3 modules: Circuit Board, AI/Coding segment, Simulation
Implemented using: Unity, C#

Circuit Board: 
Introduction to terms like resistors, power, resistance, parallel and series connection.
Simulated circuit connection using the concept of parallel and series connection. The user is expected to connect the circuit without loose connection to complete the level. The intensity of the light bulb will depend on the type of connection i.e bright -if connected in parallel and dim if connected in series. 
It contains: wires, resistors, battery, goal, none (ENUM) locked segments in the map that can’t be changed 
Gameplay: draw a line between two nodes to create a wire, 
reversible: double-click one wire to remove, 
"Test" button to check answer,
"Next" goes to the next game

Graphics: 
Circuit board (basic rectangle with circles cut inside in a grid) 8x5 grid,
Cylinder for wires,
Box for battery,
Resistor as wire with multiple triangles,
Lightbulb for goal 

AI/ Coding:

Features:
Drag and drop statements in specific order to create pseudo-code of different problem scenarios displayed as questions for the user. Code block to be dragged introduces concepts like Conditional statements (if, then, else) and Loop (while, for, wait until), Movements (forward, turn, wait) etc.
Problem statement for the user: 
Q. What happens when a car approaches a traffic light?
Q. What happens when a car approaches a “STOP” sign before a train comes?
Q.When the train is gone, loop till speed is 40 miles/hour?
Q.What happens when a car approaches a pedestrian crossing the road?
Q.What happens when a car is on one-way road and the speed limit is 40miles/hour?
Q.What happens when a car has to take a U-turn.
Q.What to do when the car enters a highway with speed limit 65miles/hour?
Q.What happens if a car has to park itself?

Simulation:
Simulates the code implemented in the AI section.
