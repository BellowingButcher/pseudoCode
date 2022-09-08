# Driving a Remote control car

## Functionality
To drive a remote control car you need a few things. A car to drive, a remote control to control the car, and batteries to power both the car and controller.

The user needs to be able to turn the car and controller on, then with the push of some buttons, move the car forward or backwards, and be able to turn left or right at the same time.  

The car needs to be able to distinguish if it has power or not display light for power on. It needs to actively listen for commands from the controller. Turn those commands into movements and execute movements. Then stop moving when the controller stops giving command, i.e. letting go of the gas or break.

The controller needs to be able to distinguish if it has power or not. If it does display power on light. Then it needs to take the input from the user and transmit it to the car. Gas, break, turn left or right.

## Objects
- Remote controller
    - Transmitter
    - Reciever
    - Battery Compartment and Battery
        - Door to access the battery compartment to replace battery
        - Springs to contact battery terminals and hold batteries in place
        - Which ever types of batteries and how many batteries it takes

    - Power Light
        - LED light
        - Wire connecting light to see if the battery has power after the On/Off switch is in the on position
    - On/Off switch
        - a circuit that either is open or shut
        - a switch to open or shut the circuit
        - the circuit sends power from the battery to the whole controller
    - Control board (buttons for moving the car)
        - Gas toggle
            - forward
            - backwards
            - no movement
        - Steering toggle
            - Left
            - Right
            - Return to Center
    - Body of controler (how do you hold it?)

- Remote Car
    - Body
        - Motor for back wheels
        - Motor for steering the front wheels
        - Wheels
    - Reciever
    - Control Board
    - On/Off switch
    - Power light