# Bloch Sphere Visualization #

This is a visualization of a Quantum bit (Qubit) and several Quantum gates using a Bloch Sphere. Quantum gates are transformations to a qubit. These transformations are visualized through rotations of a globe. A globe is used for easy understanding of 'north' (0) and 'south' (1) pole of the sphere. 

This visualization includes an easy to use visual interface. 

Gates available are: Hadamard (H), Pauli X, Y, and Z, Phase Shift (S), Pi/8, and Square Root Not.

Demo: 

[![Bloch Sphere Demo](http://img.youtube.com/vi/qCtB8S7VG8U/0.jpg)](http://www.youtube.com/watch?v=qCtB8S7VG8U)

[https://www.youtube.com/watch?v=qCtB8S7VG8U](https://www.youtube.com/watch?v=qCtB8S7VG8U)

Project Page: [here](https://tqdlab.wordpress.com/portfolio/phd-research-project-quantum-gate-and-qubit-visualization-using-a-bloch-sphere/) 

Created By: Tyler Dwyer

Creation Date: February, 2014

Contact: tdwyer@sfu.ca


### Usage instructions: ###
Edited by: Brandon Kamaka

1) Install python 2.7, x86-64.

2.) Create a project folder in an appropriate location

3.) Create a python virtual env in your project folder

4.) Activate your virtual environment

5.) pip install numpy
 
6a) Use the legacy vPython installer included in this repo: VPython-Win-64-Py2.7-6.11.exe
6b.) Uncheck the "numpy", "Demo Programs" and "VIDLE" options from the vPython installer
6c.) Choose an empty, temporary folder for your installer destination.

7.) After vPython installs into the temporary folder, open [temp folder]>Lib>site-packages and copy its entire contents 
    into [project folder]>[virtual env name]>Lib>site-packages

8.) Run bloch_Sphere_Win.py

But more importantly, you will NOT be able to run Bloch_Sphere.py, you need more for that.

3) Install numPy (A math/science package for Python, for the windows copy I got it here: http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy (Version 2.7 again)

That *should* get it working. Email me if you run into troubles.