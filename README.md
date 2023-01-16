AI that plays the first-person shooter game Half-Life 2: Deathmatch.
Moves, aims, shoots, reloads & respawns autonomously.
Uses a combination of IgaoGuru's CS:GO Sequoia neural network
for player detection and Alzaib's GTA 5 self-driving car neural network for pathfinding.

Installation:
1. Make sure python version is 3.7 or 3.8, some modules will not work with the latest versions of python.

2. Install required modules by running the command 'pip install -r requirements.txt'

3. Install Nvidea CUDA toolkit https://developer.nvidia.com/cuda-toolkit

4. Install pytorch https://pytorch.org/get-started/locally/

5. Place contents of 'files_for_game' into respective directories

6. Make sure game window is 1280x720 windowed mode, and is located at the top left corner of screen

This project was built on top of other works, listed below:

IgaoGuru's CS:GO Sequoira neural network:
https://github.com/IgaoGuru/Sequoia

Alzaib's GTA 5 self-driving car:
https://github.com/Alzaib/Autonomous-Self-Driving-Car-GTA-5