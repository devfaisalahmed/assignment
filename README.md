```javascript
/*
* Problem 1: Write a function to calculate the area of a triangle.
*/
function calculateTriangleArea(base, height) {
return (base * height) / 2;
}
let result = calculateTriangleArea(5, 3);
//console.log('The area is '+ result);

/*
* Problem 2:  convert degrees to radians.
*/
function degreeTooRadians(degree) {
  const pi = 3.141592653589793;
  let radians = (degree * pi) / 180;
  return radians;
}
//console.log("The radians is " + degreeTooRadians(10));

/*
*Problem 3: Create a function calculateFactorial that takes a number and returns its factorial.
*/
function calculateFactorial(number) {
  let initial = 1;

  if (number === 0 || number === 1) {
    return 1;
  } else {
    for (let i = 2; i <= number; i++) {
      initial = initial * i;
    }
    return initial;
  }
}
//console.log(calculateFactorial(4));

/*
* Problem 5: Create a function mergeArrays that takes two arrays as parameters and returns a new array that merges both arrays.
*/

function mergeArray(arrayOne, arrayTwo) {
  let newArray = arrayOne.concat(arrayTwo);
  return newArray;
}

let arrayOne = [1, 2, 3];
let arrayTwo = [4, 5, 6];
const n = mergeArray(arrayOne, arrayTwo);

/*
* Problem 6: Create a function isLeapYear that takes a year as a parameter and returns "This is a leap year" if it's a leap year, and "Not Leap year" otherwise.
*/

function isLeapYear(year) {
  if (year % 400 === 0 || (year % 4 === 0 && year % 100 !== 0)) {
    return  year + ' This is a leap year';
  } else {
    return year + ' Not Leap year';
  }
}
// console.log(isLeapYear(2020));

/*
* Problem 10: Create a function called evenOdd() that takes a string as a parameter. Now you have to give the output based on the total number of characters in your String. The output will be 'even' or 'odd'. [ Input: ‘JavaScript’ Output: even, Input: ‘Hello’ Output: odd]
*/
function evenOdd(parameters) {
  let parameterLength = parameters.length;
  if (parameterLength % 2 === 0) {
    return "Even";
  } else {
    return "Odd";
  }
}










```
