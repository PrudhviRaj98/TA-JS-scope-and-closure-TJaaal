1. What does thread of execution means in JavaScript?
Ans:thread execution means executing the series of steps
2. Where the JavaScript code gets executed?
Ans:code gets executed in global context
3. What does context means in Global Execution Context?
Ans:context means the environment in which we are executing the code
4. When do you create a global execution context.
Ans:when a program starts executing
5. Execution context consists of what all things?
Ans:it consists of memory and excetuion or computation
6. What are the different types of execution context?
Ans:fucntion execution context  and global execution context
7. When global and function execution context gets created?
Ans:global execution context when we start a program it is created by javascript engine where as function execution context is created by function
8. Function execution gets created during function execution or while declaring a function.
Ans:while declaring a function

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