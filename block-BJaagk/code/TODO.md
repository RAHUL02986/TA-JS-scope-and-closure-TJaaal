1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

//
 let percentage = (marks, total) {
  return (marks * 100) / total;
 }

 let percentage = (marks,total)=>{
  return (marks * 100) / total;
 }

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let percentage = function (marks, total){
  return(marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

//answer
let percentage = function(marks, total) {
  return (marks * 100) / total;
};


```


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
//answer
function less10 (num) {
  return num - 10;
}
// function dedeclaration

let less10 = function (num){
  return num - 10;
}

//function Expression

4. Why is a function call an expression in JavaScript?
As function is an object in JavaScript. Thus, if a function is stored in a variable in an expression form it's known as function expression.



5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; //valid
five = five(10, 11); // valid
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.

Function defination is when we define a function and function call is when we execute the function.

function less10 (num) {
  return num - 10;
} // Function Defination

less10 (20); // Function call
7. What is the similarities between function definition and function call?
Similarty is execution of a function.



8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.
ans-- Functions such as filter(), map(), reduce(), some(), etc, all are examples of Higher-Order Functions.
```js
let number = [1, 2, 3, 4, 5, 6];
let isEven = (num) => {
  return num % 2 === 0;
}
let isOdd = (num) => {
  return num % 2 !== 0;
}
function filter (arr, cb) {
  let array = [];
  for (let i of arr) {
    if (cb(i)) {
      array.push(i);
    }
  }
  return array;
}
console.log(filter(number, isOdd));
console.log(filter(number, isEven));
```

10. Explain what is callback function. Why you can pass a function inside a function?
ans --- A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.