# Vehicle Builder

A typeScript command-line application that builds and uses cars to have additional options for motorbikes and trucks. The application prompts the user to create a new vehicle or select an existing vehicle. After going through the creation process or the selection process, the user is able to perform certain actions with the selected vehicle. The user is returned to the actions menu after each action until they decide to exit the application.

## Features
1. Create and manage different types of vehicles: Car, Truck, Motorbike.

2. Perform actions such as starting, accelerating, decelerating, stopping, turning, and reversing vehicles.

3. Specific actions for trucks to tow other vehicles and the ability to perform a wheelie with motorbikes.

Interactive CLI using Inquirer.js

## Installation
To get started with the Vehicle Management CLI, follow these steps:

1) Clone the repository:
    
    ```
    git clone 
    ```
    
2) Install inquirer:

    Ensure you have Node.js installed. Then open integrated terminal and run:
        
        npm install
        

    To start the CLI application, run the following command:

        npm run start

## Available Actions
Print Details: Display detailed information about the selected vehicle.
Start Vehicle: Start the selected vehicle.
Accelerate 5 MPH: Increase the speed of the selected vehicle by 5 MPH.
Decelerate 5 MPH: Decrease the speed of the selected vehicle by 5 MPH.
Stop Vehicle: Stop the selected vehicle.
Turn Right: Turn the selected vehicle right.
Turn Left: Turn the selected vehicle left.
Reverse: Reverse the selected vehicle.
Tow a Vehicle: Only available for trucks to tow other vehicles.
Perform a Wheelie: Only available for motorbikes.
Select or Create Another Vehicle: Go back to the main menu to select or create another vehicle.
Exit: Exit the CLI application.

## License
This project is licensed under the MIT License

## Link to a demo


