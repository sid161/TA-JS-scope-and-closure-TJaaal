1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function(marks, total) {
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
}
```


2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let percentage = function(marks,total){
  return (marks * 100) / total;
}

```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
function percentage(marks,total){
  return (marks * 100) / total;
}

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.


4. Why is a function call an expression in JavaScript?
Because function is an object in javascript and object can be stored so a function is stored inside variable

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}  

let five = add(2, 3); // valid function stored in variable
five = add; // Answer // invalid
five = five(10, 11); // invalid
five = function () {
  return 'Hello';
}; // invalid
```

6. What is the difference between function definition and function call? Explain with an example.
function definition is how a function is declared syntax of function and function call is how a function is executed
 below is function definition
function add(num1,num2){
  return num1 + num2;
}

function call
add(1,3);

7. What is the similarities between function definition and function call?


8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // 

invalid
```

9. What is higher order function explain with an example.
a function that accepts and return another function is called higher order function
sayHi = (name) => `Hi, ${name}!`;
result = sayHi('User');

console.log(result);

10. Explain what is callback function. Why you can pass a function inside a function?
A callback is a function passed as an argument to another function.
