1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

Answer - In this function return is used so that the finction is correct.
        in return datatype will defined.


// second
function sum(a, b) {
  console.log(a + b);
}
```
Answer - In this function return is not used so the function is wrong.
        in this datatype will not be defined.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Answer - `first` sum(9, 6) = 15
                    
          `second` sum(9, 6) = 15
                    

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

function sum(a, b, c) {
  return a + b + c;
}
sum(12, 24, 35)


4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

 yes we can do that.

  function add(a, b) {
  return a + b;
}

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function sayHello(name){
    return `hello Arya`
}


6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();'Hello, John'
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 
  'John'

showMessage(); // Output 2
  'Hello, John'

alert(userName); // Output 3
  `john`

```

8. What is a Anonymous Function give example of three functions.

Answer - 

An anonymous function is a function that was declared without any named identifier to refer to it.

const addNumber = function(numA, numB){
  return numA + numB;
}

const multiplyNumber = function(numA, numB){
  return numA * numB;
}

const substractionNumber = function(numA, numB){
  return numA + numB;
}

const divideNumber = function(numA, numB){
  return numA + numB;
}



9. Can function declaration be a Anonymous Function? Explain

One can define "named" function expressions (where the name of the expression might be used in the call stack for example) or "anonymous" function expressions. Function expressions are not hoisted onto the beginning of the scope, therefore they cannot be used before they appear in the code.


10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
