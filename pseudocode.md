# Driving a Remote control car

## About RC cars
To drive a remote control car you need a few things. A car to drive, a remote control to control the car, and batteries to power both the car and controller, and a user to decide where and when to move.

The user needs to be able to turn the car and controller on, then with the push of some buttons, move the car forward or backwards, and be able to turn left or right at the same time.  

The car needs to be able to distinguish if it has power or not display light for power on. It needs to actively listen for commands from the controller. Turn those commands into movements and execute movements. Then stop moving when the controller stops giving command, i.e. letting go of the gas or break.

The controller needs to be able to distinguish if it has power or not. If it does display power on light. Then it needs to take the input from the user and transmit it to the car. Gas, break, turn left or right.

## Objects
- Remote controller

    - Transmitter 
        - Each movement button is tied to a spacific radio wave pulse known as hertz
        - No two buttons use the same hertz
        - Transmitter waits for an electric conection to be made when the joy sticks are moved.
            - It should be able to transmit two radio waves at once
                - If the user is inputing (forward or backwards) AND if the user is (inputing left or right).

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
                - This is a joy stick that can move in two directions, forward and back. When released it returns the stick back to center. Stopping any forward or backward movement of the wheels.

        - Steering toggle
            - Left
            - Right
            - Return to Center
                - This is a joy stick that can only move in two directions, left and right. When released the stick returns to center. Returning the steering column to center.
    - Body of controler (how do you hold it?)

- Remote Car

    - Body

        - Motor for back wheels
        - Motor for steering the front wheels
        - Wheels

    - Reciever

        - listening for spacific hertz radio waves from the controller

            - Move car forward
                - Start when connection is made
                -Stop when connection is broken

            - Move car backwards
                - Start when connection is made
                - Stop when connection is broken

            - Steer Wheels right
                - Move wheels to steer right when connection is made
                - Return to center when connection is lost

            - Steer wheels left
                - Move wheels to steer left when connection is made
                - Move wheels to center when connection is lost

    - Control Board
        - Listens to the comands from the reciever and executes the commands
            - Tells what motors to run and when

    - On/Off switch
        - If the switch is on then power the car
        - If switch is off then the car has no power
        
    - Power light
        - If the car has power display light
        - else light off