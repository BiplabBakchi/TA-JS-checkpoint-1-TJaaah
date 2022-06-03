1. Using loops take 10 inputs from user and find the average of all the numbers.
```js

```
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```


3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
 

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.
```js
function getProductOfDigits(num) {
  let product = 1;
  while (num != 0) {
      product = product * (num);
}
return product;
}
getProductOfDigits(2,7, 8,5);
```

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output 'Bigger than 5' An if statement needs an expression if the expression evaluates to true then the true block is executed.
check(1); // output 'Smaller than 5'  An if statement needs an expression if the expression evaluates to true then the true block is executed.
check(5); // output '5' An if statement needs an expression if the expression evaluates to true then the true block is executed.
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output 'You are arya' We are getting the output 'You are arya' because we get the output according to the arguments defined in the function call. 
getOutput('John'); // what will be the output 'You are john' We are getting the output 'You are John' because we get the output according to the arguments defined in the function call. 
getOutput(); // what will be the output 'Who are you'  We are getting the output 'Who are you' because we have not defined any arguments in the function call so the default return value is returned to us.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output // "Who are you" On calling the functions we get the out put "Who are you" because we only get the value of return statement and the value of return statement is 'Who are you'.
getOutput('John'); // what will be the output // "Who are you" On calling the functions we get the out put "Who are you" because we only get the value of return statement and the value of return statement is 'Who are you'.
getOutput(); // what will be the output // "Who are you" On calling the functions we get the out put "Who are you" because we only get the value of return statement and the value of return statement is 'Who are you'.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
// No a function cannot have multiple return statement it can only have one return statement'

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.// 
