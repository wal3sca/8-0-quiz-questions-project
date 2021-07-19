ARRAYS & OBJECTS

Q1: What is an array?

A1: An array allows you to store multiple values inside of a variable. An array will always contain square brackets []. However, arrays don’t always need to contain values. You can have an empty array and use different methods to add values to the array.

EXAMPLE: 
const sweaterWeather = [50, 55, 60, 65]

The array above displays that the variable ‘sweaterWeather’ is an array. The values inside of the array are numbers that represent the different temperatures in which it is appropriate to wear a sweater.


Q2: What does an index mean in an array?

A2: The index in the array is the position that the element within the variable falls in. All indexes begin at 0. Therefore, if the length of the array is 6, the index of the last element would be 5.

EXAMPLE:
const array = [A, B, C, D, E, F, G]

The length of the array is 6; the index of A is 0, the index of B is 1, the index of C is 2...and so on.

Q3: Hardcode the following pseudocode: If the array is empty log out “This array has no elements”

A3: if (arr.length === 0) { console.log(“This array has no elements”) } 
One way to describe an array is using the array property length. 
[‘A’, ‘B’]  The length of this array is 2 
[‘A’]  The length of this array is 1
[] The length of this empty array is 0
Using a strictly equal to we can compare the arr.length to zero and console log the string “This array has no elements.

Q4: Which of the following is an example of an array and which is an example of an object?

let clothes = ["shirt", "jeans", "skirt", “tank top”];

let clothing = {
  cute: true,
  wearable: "yes",
  name: "shirt",
};

Clothes = _______		Clothing = __________

A4: Clothes = Array 		Clothing = Object 