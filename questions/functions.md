FUNCTIONS

Q1. What would the text inside the parenthesis be called in this function below? What does that mean?

function carParts (doors, tires, windows)

A1: Doors, tires and windows are the parameters of the function. Parameters identify what will be declared into the function. This data are the values of the arguments that will be evaluated.


Q2. What is a return value in a function?

A2.  A return value stops the code from executing and returns a value from that function.

EXAMPLE: 
function astroWorld (sun, moon) {
	return sun * moon;
}

The return value of the function is the product of the parameters “sun”and “moon”. The function will not continue to execute as long as that return statement is in the function.


Q3. Given the following function, properly invoke the function and log out the return.

function even (num) {
	if (num % 2 === 0) {
	return `${num} is an even number`
	} else {
	return `${num} is an odd number`
	}
} 

A3. To invoke the function you need to use the following syntax: functionName(argument). To log the return into the console you need to you use: console.log()
In one line you can: console.log(even(10))
Or: const functionOutput = even(10); 
      console.log(functionOutput);

Q4: In a function, one part requires something (data in some form) to be given to the computer and/or program. Another part is the program and/or computer giving something back based on the data. Which part of the function, input or output, is each listed below?

The actual end product or result after a specific process is run and data is used, this is called the ________. 

Instructions and data are given to create a desired intended outcome, this is called the _______. 

A4: a. Input 
      b. Output 

