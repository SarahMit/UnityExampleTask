# UnityExampleTask

These tasks are designed to test out necessary skills concerning scripting, ray casting, data structures, creation and deletion of objects, materials, and shaders in Unity.

### Preparation
* Install Unity 2021.3.6f1 LTS
   * Install [Unity Hub](https://unity3d.com/get-unity/download) first
   * Open Unity Hub and install the desired Unity version 
* Fork the GitHub repository
   * using the button on the website (upper right corner)
* then Clone the forked repository
   * Using a programm like [GitHub Desktop](https://desktop.github.com/) is recommended

### Getting to know Scripting and UI Elements
* Create a 3D Cube
* Add a script to rotate the cube by dragging the mouse
* Create a UI [Canvas](https://docs.unity3d.com/2018.3/Documentation/Manual/class-Canvas.html)
* Add a [toggle button](https://docs.unity3d.com/2018.3/Documentation/Manual/script-Toggle.html) that locks the rotation in one direction
* Change the color of the cube (e.g. by creating new simple material or shader)

### Getting to know Shaders
* Create a second cube
* Make it bigger and move the first cube inside
* Create a "Lit Shader Graph"
* In the [shader graph](https://docs.unity3d.com/Packages/com.unity.shadergraph@12.1/manual/index.html): set another color & set the transparency (alpha value) below 1
* Create a material based on your shader graph
* Apply the material to the second cube
* Find a way to rotate both nested cubes simultaneously

→  this is what your scene might look like so far:

![capture1](https://github.com/SarahMit/UnityExampleTask/blob/main/instruction/capture1.PNG)


### Working with the Shader Graph
* Create a Sphere
* Create a new shader graph
* In the shader graph include the node "Fresnel Effect" (see left image below)
* Use it to color the sphere (see example image on the right side)
     * There should be a color gradient between two colors
     * The “inner” area of the sphere should have another color than the outer areas
     * You might need the shader graph nodes called “color”, “multiply”, “subtract”, and “add” but you can also find another way to solve this.
     
![capture2](https://github.com/SarahMit/UnityExampleTask/blob/main/instruction/capture2.PNG)
     
### Ray Casting and Data Structures
* Create a new scene and work in it to perform the following steps
* Write a script that spawns objects (e.g. cubes or spheres) in the scene when you click the left mouse button
* Write a script that recognizes when you click on one of the objects and saves selected objects in a list
* Include one button that gives all the selected objects a new color when pressed
* Include another button that deletes all selected objects when pressed
* Include another button to deselect all objects

### Save your Work
* Commit your work to the repository
* Push your work
