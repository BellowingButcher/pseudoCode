# Driving a Remote control car

To drive a remote control car you need a few things. A car to drive, a remote control to control the car, and batteries to power both the car and controller.

The user needs to be able to turn the car and controller on, then with the push of some buttons, move the car forward or backwards, and be able to turn left or right at the same time.  

The car needs to be able to distinguish if it has power or not and tell the controller if it needs batteries. It needs to actively listen for commands from the controller. Turn those commands into movements and execute movements. Then stop moving when the controller stops giving command, i.e. letting go of the gas or break.

The controller needs to be able to revieve information about weither the car needs batteries display red color if battery is low, display green if battery is above 50%. Do the same for its own battery supply.

Then it needs to take the input from the user and transmit it to the car. Gas, break, turn left or right.