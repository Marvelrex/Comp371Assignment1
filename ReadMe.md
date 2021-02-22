# COMP 371 Quiz 1
To run this program, navigate to Comp371-w21-15/ src and open a A1.cpp.

Name_ID

* Jialin Yang_40069006

Quiz I

* Rendered Models, 128*128 grid, x-y-z axis in 3D space.
* Operation can be done by keyboard and mouse.
* Focused on Matrix transformation, Hierarchy Models, Camera , Input Handle.


You can See:

* Eight different colors models are to be placed vertically on postive Z axis direction grid border with x=0, y=0;
* 128*128 girds in yellow color.
* RGB xyz cylinder axes located at origin.

Brief Description:
* User can use 1-8 to bind each model, and camera will be put in front of model. When model is binded
* User can move(by UP DOWN LEFT RIGHT ARROW KEY) rotate(SHIFT + A/D) zoom(U and J). 
* Changed render type by T(GL_TRIANGLES), L(GL_LINES),P(GL_POINTS)
* Additionlly
* I added two new function.
* 1.User can press I to toggle on groupModel, the whole model can move, rotate, and zoom together.
* 2.If user bind to one model, user can press O to make model rotate around origin and press Y || bind other model to stop it.
* 3.To be more interesting, I added two U models to model's left and right side. User can rotate them around the model tower, move and scale(Same operation as other model).
*/

### Operation

Project1 used keyboard and mouse as input:

* [1] Bind model 1 Y and activated. 
* [2] Bind model 2 A and activated. 
* [3] Bind model 3 N and activated. 
* [4] Bind model 4 G and activated. 
* [5] Bind model 5 J and activated. 
* [6] Bind model 6 I and activated. 
* [7] Bind model 7 U and activated. 
* [8] Bind model 8 U and activated. 
* [W] - Move binded model away from the camera.
* [A] - Move binded model close to the camera.
* [S] - Move binded model to the left side of camera.
* [D] - Move binded model to the right side of camera.
* [W][A] Model moves diagonaly top left.
* [W][D] Model moves diagonaly top right.
* [S][A] Model moves diagonaly bottom left.
* [S][D] Model moves diagonaly bottom right.
* [SHIFT + A] Rotate model left 5 degrees.
* [SHIFT + D] Rotate model right 5 degrees.
* [U] - Scale up the model
* [J] - Scale down the model
* [T] - Change render type to GL_TRIANGLES
* [L] - Change render type to GL_LINE_LOOP
* [P] - Change render type to GL_POINTS
* [I] - Choose the whole model as a object and do operations, such as move rotation and scale
* [O] - Let binded model rotate around origin.
* [Y] - Stop rotating around origin.
* [UP ARROW] Fps-like Move Forward
* [DOWN ARROW] Fps-like Move Backward
* [LEFT ARROW] Fps-like Move to the left
* [RIGHT ARROW] Fps-like Move to the right

* [Home] Reset all model and world to inital setting.



### Todos

 - Quiz 2...