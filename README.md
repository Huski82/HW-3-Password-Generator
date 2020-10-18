# HW-3-Password-Generator

The homework assignment for UC Berkeley coding Bootcamp was to deploy a functioning application that emphasizes the use of Javascript to generate a random, secure password for the user.
My project is deployable to GitHub & the project is up and running.
I also have a link to my project demonstration.

PW Generator Project

https://drive.google.com/file/d/1k4Qr_x-wEVjnskvzBf6ykq8P7tglDror/view

<iframe src="https://drive.google.com/file/d/1k4Qr_x-wEVjnskvzBf6ykq8P7tglDror/preview" width="640" height="480"></iframe>

I also sourced from youtube how to create a "Copy to clipboard Button".
Source: https://youtu.be/9sT03jEwcaw

This project has script features of:

Variable declaration area

An event listener (onclick) called generatePassword

This will prompt the user for input between 8-128

This variable is changed to an interger using ParseInt()

This will validate that the input is a number within range, or is a number

This then uses the input to determine the types (or choices) or letters of characters used, using an if statement

This then assigns values to the variables using arrays for character, number or alphabet

Another variable is created to concatenate the above variables

A for loop will loop through the enter prompt until it reaches the number entered by user.

A password variable takes the value from the for loop, and converts it to a string.

The string value then populates into the text area for the user using a UserInput function.

An event listener (onlick) has also been created for the copy to clipboard feauture.
