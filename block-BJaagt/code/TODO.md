Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // output
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // useranme is not defined
```
In the above code we are looking for the useranme but there is no variable in the global scope. 

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // useranme is not defined

```
In the above code we are looking for the useranme but there is no variable in the global scope.but in the if statement username is defined as arya but it is a local scope and console useranme is different from username

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); useranme is not defined
```
In the above code we are looking for the useranme but there is no variable in the global scope.but in the if statement username is defined as arya but it is a local scope and console useranme is different from username

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // useranme is not defined 
```

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // username is already defined 

```

As username is already defined in the global scope moreover logging ouput is the useranme which is not same as the username

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // useranme is not defined
```
as useranme is not defined in the global scope 

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // 
}
console.log(i, 'Second'); // 1-9 is first, 10 is second

```
where i is created in the global scope as intilazied to 0 so after all repetation and completion of loop i becomes 9 

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // 1-9 is first
}
console.log(i, 'Second'); // 10 is the second
```
where i is created in the global scope as intilazied to 0 so after all repetation and completion of loop i becomes 9
