1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```
let percentage = function(marks, total){
  return (marks * 100) / total;
}

let percentage = (marks , total)=>s{
  return (marks * 100) / total;
}

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
Function Expression: percentage
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
Function Expression: percentage
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
Function Expression: percentage
```js
let percentage = (marks, total) => (marks * 100) / total;
```
Function Expression:percentage

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

because a function is an object in a javascript so if object is stored in an varibale then it is called as function expression

let marks = function(score,grade){
  return score * grade;
}

4. Why is a function call an expression in JavaScript?

because function is stored in expression so we have to call function by its varible where it is stored

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.

function defination is to define a certian steps to perform where as function call is to execute those defined steps 

7. What is the similarities between function definition and function call?

for calling and defining we use same function name

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.

a functionn that accepts onather function as an argument then it is called higher order function

function square (num){
  return num * num;
}

function calculate(fn){
  console.log(fn(2));
}
calculate(square);

10. Explain what is callback function. Why you can pass a function inside a function?
call back function basically accepts function as an argument and pass it to another fucntion 