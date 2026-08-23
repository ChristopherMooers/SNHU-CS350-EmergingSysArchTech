# CS-350 Emerging Systems Architectures and Technologies

## Project Summary

For this project, I developed a prototype smart thermostat using a Raspberry Pi. The system uses an AHT20 temperature sensor to monitor the current room temperature and an LCD to display the date, time, current temperature, operating state, and temperature set point. Three buttons allow the user to change between off, heating, and cooling modes and increase or decrease the desired temperature. Red and blue LEDs provide visual indicators for heating and cooling. The project also uses UART communication to simulate sending thermostat data to an external server.

## What Did I Do Particularly Well?

I think I did particularly well integrating the different hardware and software components into one working system. Throughout the course, I worked with GPIO, I2C, UART, LEDs, buttons, the LCD, and the temperature sensor separately before combining them for the final project. Breaking the project into smaller components made it easier to test each part and troubleshoot problems before putting everything together.

## Where Could I Improve?

One area I could improve is planning the physical layout of the circuit before connecting all of the components. As more components were added, the breadboard became crowded and the wiring became more difficult to follow. I also noticed that button presses could occasionally cause the temperature set point to change more than once. Additional button debouncing and testing could make the controls more consistent.

## Tools and Resources

This project gave me more experience using Raspberry Pi, Python, GPIOZero, I2C, UART, VS Code, PowerShell, and draw.io. I also learned the importance of using documentation, wiring diagrams, test programs, and incremental testing when troubleshooting embedded systems. These are resources and approaches that I can continue using when working with unfamiliar hardware and software.

## Transferable Skills

The troubleshooting and problem-solving skills from this project will transfer well to future software development projects. I learned to isolate problems, test individual components, and verify that each part works before integrating it into a larger system. I also gained experience connecting software directly to hardware and using a state machine to control system behavior.

## Maintainability, Readability, and Adaptability

I kept the thermostat software organized by separating different responsibilities into methods and using a state machine to manage the operating modes. Descriptive names and comments make the purpose of the code easier to understand. Separating functions such as temperature readings, display management, button handling, and LED control also makes the program easier to modify or expand without having to redesign the entire application.
