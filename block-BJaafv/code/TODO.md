1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
// First `sum` function has return statement so it will return the value but Second  `sum` function has no return statement and as it has console.log it will log the value and return the value undefined

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
// Value of first will be sum of a + b but value of second is undfined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
// 36 Because a and b parameters are only available in the fuction.
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
// Yes we can store the first `sum` function in a variable named `add`.Because it has a return statement

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
// function sayHello(name) {
  return `Hello ${name}`;
}
sayHello(`arya`);

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
// Output will be 'Hello, John' because user name is defined outside the funtion 
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 "John"
 
showMessage(); // Output 2 "Hello, John"

alert(userName); // Output 3 "John"
```
8. What is a Anonymous Function give example of three functions.
// const addNum = function(a, b) {
    return a + b;
  };
9. Can function declaration be a Anonymous Function? Explain
// No function declaration cannot be an Anonymous Function Because we cannot call the function.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.


```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with???

"get???" ??? return a value,
"calc???" ??? calculate something,
"create???" ??? create something,
"check???" ??? check something and return a boolean, etc.
```
//addNumbers,subtractNumbers,getName,calcNum,calcAge