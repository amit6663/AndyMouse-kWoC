## AndyMouse-kWoC
This is the project of AndyMouse, basically to control mouse movements by android app.
### skills needed
Android studio(java, xml design), Bottle library of python.
### location directory
sensor.py contains the server side code, it is a bottle(a python library) based restful server.

in the AndyMouse folder all the android app code is placed.

### working principle
The android appis a bottle client here. Also the app collects the accelorometer data and calculates the the tilting along X and Y axis. And sends the tan of that angle to the server as a json format.

