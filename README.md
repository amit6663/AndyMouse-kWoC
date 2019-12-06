## AndyMouse-kWoC
This is the project of AndyMouse, basically to control mouse movements by android app.
### plase go through [THIS](https://docs.google.com/presentation/d/1v2q9_JhMh9z1giz6h9mKU9XZ4hZ3JlYG2z34-czweeQ/edit?usp=sharing) slides(mainly endsem one) to know about the project.
### skills needed
Android studio(java, xml design), Bottle library of python.
### location directory
sensor.py contains the server side code, it is a bottle(a python library) based restful server.

in the AndyMouse folder all the android app code is placed.

### working principle
The android appis a bottle client here. Also the app collects the accelorometer data and calculates the the tilting along X and Y axis. And sends the tan of that angle to the server as a json format.
and our server (sensor.py) is a bottle server and it takes the 2 ratio value and a very simple math to output the mouse pointer movement.
we used pyautogui python library to move the mouse pointer and the slide changes.

