# Deployable-Solar-Array-Controller
The deployable solar array controller is used to deploy the Origami-based Solar Array mechanism. It is implemented using Arduino Nano. Please visit the project page for more details: http://swapneelnaphade.site/projects/origami-based-deployable-solar-array 
 
 <p align="center"><img width="500" src="http://swapneelnaphade.site/wp-content/uploads/2018/12/image074.jpg"></p><br>

The circuit is as shown in the above figure of an Arduino Nano soldered onto a perf board.

 <p align="center"><img align="center" width="500" src="http://swapneelnaphade.site/wp-content/uploads/2018/12/image067-300x185.jpg"></p><br>

The servo motors are attached to the mechanism as shown in the above CAD image.


## Commands
The following commands can be sent through the UART port of Arduino Nano:
- "d" or "D" -> Starts the deployment process
- "r" or "R" -> Starts the retraction process
- "f xxx" or "F xxx" -> Changes the full swing angle of mechanism by xxx degrees.
- "t xxx" or "T xxx" -> Changes the step time of mechanism motion by xxx milli-seconds.
- "w xxx" or "W xxx" -> Changes the angular velocity of mechanism motion by xxx degrees/second.
- "p" or "P" -> Pauses/Unpauses the mechanism motion.

 
