Javascript Test
Just a quick test to test your javascript understanding.

1- What is ES6?

Ecmascript is a standardization for creating a scripting language. Es6 is A version that makes it easier to write and read (with const and let).


2- Name 3 examples of ES6 features.

const
let
arrow function


3- What is the difference between let and const?

while let can be updated decleration const cannot be updated declaration


4- How do you access object values? Give 3 examples

Object.keys()
Object.values()
Object.entries()


5- What does setInterval and setTimeout do?

setTimeout: It is a function that we can use if there is a code block that we want to run after a certain time has passed.

setInterval: A function that repeats an operation at certain time intervals



6- What are promises?

Promises in JavaScript are objects that handle asynchronous operations, which are processes that are already happening or will happen in the future.



7- Convert this async function to async/await
getQuote().then((quote) => {
  console.log(quote);
}).catch(function(err) {
  console.log(err);
});
// after this line,



8- Convert this code to arrow function.
function greeting(firstname, lastname) {
  return `Hello ${firstname} ${lastname}`;
}
// after this line,

function greeting(firstname, lastname) => `Hello ${firstname} ${lastname}`;



9- Explain what a callback function is.

Callback is a function that we give as a parameter to any function and then call back.


10- What does the functions pop and push do to an array?

pop: removes the last element from an array and returns that element.
push: adds the specified elements to the end of an array.



11- What is the expected answer to this code?
let string = "";
let object = { a: 1, b: 2, c: 3 };
for (let key in object) {
  string += object[key];
}
console.log(string);

123


12- What data type would Array.map() and Array.filter() return?

Array.map(): array.map() creates a new array matching the called condition

Arrat.filter(): The given array is used to filter the array according to the spesific condition. 


13- What data type would Array.includes() and Array.some() return?

Array.includes(): this method determines whether an array contains a certain value among its entries and returns true or false.

Array.some(): If there is an element in an array that meets the specified conditions, our result will return true. If not, it will return false.

14- Write down the 4 main methods of rest api

HTTP GET
HTTP POST
HTTP PUT
HTTP DELETE

15- What is the difference between JSON and a JavaScript object?

JSON is a notation method for passing data in javascript objects between different languages.