1. Using loops take 10 inputs from user and find the average of all the numbers.

```js
var sum = 0

function calcSum(){
for(let i = 0 ; i <10 ; i ++){
   number = Number(prompt("enter the number"))
    sum = sum + number   
}
  return sum
}

sum = sum + calcSum()

alert(`the average is ${sum/10}`)

```



2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

answer => error beacuse println is not defined.

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

answer => 
```js
var sum = 0;

function getEvenSum(max = 10){
   for(let i = max ; i>0 ; i--){
     if(i%2 == 0){
        sum = sum + i
        console.log(sum) 
     }
   }
   return sum 
}

getEvenSum(20)
getEvenSum()
```



4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

answer => 
```js
var sum = 0;

function getOddSum(max = 10){
   for(let i = max ; i>0 ; i--){
     if(i%2 != 0){
        sum = sum + i
        console.log(sum) 
     }
   }
   return sum 
}

getOddSum(20)
getOddSum()
```


5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

```js

var num = prompt("enter the number it will give the product of the number")
var  multiply = 1;
function getProductofDigits(num){
  if(isNaN(num) == true){
     return `not a valid input`
 }
   else if(Number(num) < 0){
    return `Invalid Input`
  }else{
    for(let i = 0 ; i < num.length; i++){
      let str = num 
      multiply = multiply * Number(str.slice(i,i+1))
    }return multiply 
  }
}
getProductofDigits(num)

```

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

check(10); // output
check(1); // output
check(5); // output
```


answer => for first output will be the bigger than 5 beacuse , number is less than 5, check(1) output will be the less than 5 it follows less than conditon for last it will return num.
 
7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```
answer => # output will be the `You are arya` , for getOutput('John') will be the `You are john` and getOutput() return `Who are you` because it is according to the condition. 


8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

answer => no it can not possible it have multiple return statement if we want more we can use array.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.


answer => for loop is condition pre determined but while loop run  till function condition get false.


# for
for(let i = 0 ; i < num.length; i++){
      let str = num 
      multiply = multiply * Number(str.slice(i,i+1))
    }return multiply

# while
let i = 0
let num = prompt("enter the number")
let multiply =1

while( i < 4){
      multiply = multiply * Number(num)
    i = i +1
    }
console.log(multiply)
console.log(i) 









