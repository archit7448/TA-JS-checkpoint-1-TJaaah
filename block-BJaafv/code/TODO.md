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

answer => first will return the value by adding it to the call but second will show in console sum.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

answer=> first value will be the sum but in the second will be the undefined.


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

answer => sum function in first add first two vakues and last value have no impact because it is not in parameter it will ignore it.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

answer => yes I can store the values because this expression is valid beacuse we are storing the value .

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

answer => 
```js 
// first
function sayHello(name){
  return `Hello ${name}`
}

sayHello(Arya)

```


6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
answer => output of this function will be 'Hello, ' + userName ;


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // it will show in the alert  John

showMessage(); // it will return Hello, John

alert(userName); // Output 3 it will alert John
```

8. What is a Anonymous Function give example of three functions.

```js
let add = function (a,b){
  return a + b;
}

let subtract = function (n){
  return n*n
}

let multiply = function (x,y){
  return x*y
}

```

9. Can function declaration be a Anonymous Function? Explain

answer => no it can't be the annnymous function, because in declaration of function we give the name.

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



```js
function getValue(a,b){
    return a * b
}


function checkString(v1,v2){
  if(typeof v1 == "string" && typeof v2 == "string"){
    return true
  }else {
    return false
  }
}

function checkNumber(v1,v2){
  if(typeof v1 == "number" && typeof v2 == "number"){
    return true
  }else {
    return false
  }
}


function calcMultiply(a,b){
  let multiply = a*b
  return multiply
}

function calcDivide(a,b){
  let divide = a / b
  return divide
}


```


