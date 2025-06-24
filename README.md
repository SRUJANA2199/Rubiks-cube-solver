# Rubiks-cube-solver

Object-Oriented Cube Structure:
I structured the cube using a Cube class in JavaScript. Each side of the cube (Up, Down, Front, Back, Left, Right) is stored as a 3x3 grid using arrays. 

Manual Rotation of Cube Sides:
I implemented a manual rotation for the top face (U). When it’s rotated, the top row of adjacent faces also shifts accordingly to reflect how a real cube behaves.

Scramble Functionality:
It applies randomly U-face rotations and stores each step, mimicking the way a cube gets shuffled before solving.

Solving Logic:
For the solving part, I used a simple method: reverse the scramble moves step-by-step.
Project hosted in :
 https://srujana2199.github.io/Rubiks-cube-solver/
