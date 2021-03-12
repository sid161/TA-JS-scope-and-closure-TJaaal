1. What does thread of execution means in JavaScript?
thread of execution means the processes which takes place in javascript engine for execution

2. Where the JavaScript code gets executed?
global execution context

3. What does context means in Global Execution Context?

4. When do you create a global execution context.
each time when javascript program runs

5. Execution context consists of what all things?
code execution context and memory
6. What are the different types of execution context?
global execution context and function execution context

7. When global and function execution context gets created?
global execution context is created when js engine is executing code whereas function execution context is created when function gets executed

8. Function execution gets created during function execution or while declaring a function.
function execution


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)