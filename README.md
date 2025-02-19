# Vehicle Builder

## Description
This is a TypeScript command line application that builds and uses cars, trucks, and motorbikes.

## Table of Contents
- [Installation Instructions](#installation-instructions)
- [Usage Information](#usage-information)
- [License](#license)
- [Contribution Guidelines](#contribution-guidelines)
- [Testing Instructions](#testing-instructions)
- [Questions](#questions)
- [Resources](#resources)

## Installation Instructions
**Node.js:** Ensure you have Node.js installed (latest release).
**npm:** Make sure you have npm installed via node.js.
1. Download repository
2. In terminal, run `npm install inquirer typescript`
3. In terminal, navigate to src/
4. In terminal, run `npx tsc`
5. In terminal, run `npm run start`

## Usage Information
[![Video Demo](https://cdn.loom.com/sessions/thumbnails/4668dc53a4594378881be2974f72f3a5-d8d01b8ebb8f8a91-full-play.gif)](https://www.loom.com/embed/4668dc53a4594378881be2974f72f3a5?sid=435420ad-56bf-461b-afcd-db9e9aa52a69)

GIVEN a command-line application that accepts user input
WHEN I am prompted to create a new vehicle or existing vehicle
THEN I can choose between the two options
WHEN I am prompted to choose the vehicle type during creation
THEN I can choose between car, truck, and motorbike
WHEN I am prompted for details about the vehicle
THEN I can enter the vehicle information
WHEN I have entered all the vehicle information
THEN I can use the created vehicle
WHEN I select an existing vehicle
THEN I can use the selected existing vehicle
WHEN I have created a new vehicle or selected an existing vehicle
THEN I can perform actions with that vehicle
WHEN I perform an action with a vehicle
THEN I see the result of the action in the command-line
WHEN I complete the process of performing an action
THEN I can perform additional actions until I choose to exit

## License

 ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

 This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.

## Contribution Guidelines
This application is not accepting contributions at this time.

## Testing Instructions
To use the application, download repository. In command line, use `npm run start` to initiate. 

Example test case:
- Initiate application via `npm run start`
- Choose "Select an existing vehcile"
- Choose Ford F-150
- Choose Print Details
- Expected Result: application will print vehicle details and display list of actions. The details show should list the following data: Vehicle Started, Vehicle Current Speed, VIN, Color, Make, Model, Year, Weight, Top Speed, Towing Capacity, Wheel 1, Wheel 2, Wheel 3, Wheel 4.

## Questions
For additional questions an instructions, please contact me at elli.mckinley@gmail.com.

Checkout my other GitHub projects: @ellimckinley.

## Resources
No additional resources were used
