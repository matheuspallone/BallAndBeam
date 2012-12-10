# Ball and Beam

## About

This model was built for the Washington University in St. Louis Systems Engineering Laboratory by Philip Thomas, Nicole Schreiber, and Allison Doren. 

This model implements cascaded feedback loops to control the position of a ball bearing on a beam. The inner loop models the movement of the motor, while the outer loop models the movement of the ball and beam. While input may be a square wave or a sinusoid, we implemented a sensor consisting of sparate ball and beam, where we manually manipulated the position of the ball as an input. The system thus reads the input of one ball and beam system, then mimicks it on the other system. 

## Demo

Video coming soon

## Design Specifications

* No steady-state error
* .15 second time to peak
* 5.0% overshoot
