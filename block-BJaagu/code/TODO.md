Find the output of the code snippets below:

```js
console.log(numA + numB); //undefined + undefiend = NAN
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //numA has already been declared.
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); //
function sayHello() {
  console.log("Hey");//
}
function sayHello() {
  console.log("Hello");// hello
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello();
function sayHello() {
  console.log(username);//Tyrion
}
```

Find the output of the code snippets below:

```js
sayHello(); // error
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // sayhello has already been declared
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // sayhello is already been declared.
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // sayHello has already been declared
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello();
let sayHello = () => {
  console.log(username);//undefiend
};
```

Find the output of the code snippets below:

```js


var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); //john
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); //error
```