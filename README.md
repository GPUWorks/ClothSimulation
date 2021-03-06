# Cloth Simulation using Spring Mass Model and Internal Energy Model

There are two models which have been tried. One is called **Spring Mass Model** and the other is called **Internal Energy Model**. Each model is located in a separate folder.

A glimpse of the output:
![Spring Mass Model](/springmass/simulation/simulation.gif)


Follow the steps to get the code running:

1. Install OpenGL, GLUT and GLM.

2. Clone the repo.

3. Compile each model using the command 
```
g++-5 *.cpp *.h -std=c++11 -lGL -lglut -lGLU
```

4. Run the executables. Use the 'W','A','S','D','R','F' to move the camera and the 'I','J','K','L','Z','X' keys to rotate the camera and look around.

Refer to the HTML documentation in the 'documentation' folder to learn more about the project. Code documentation generated using doxygen can be found in 'html' folders of the individual models.

Other collaborators: [@anikethjr](https://github.com/anikethjr/) and [@many-facedgod](https://github.com/many-facedgod)
