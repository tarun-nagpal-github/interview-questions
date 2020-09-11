## Below is the combined list of interview questions for JavaScript


https://github.com/lydiahallie/javascript-questions﻿


Difference between undefined and null?

What is the prototype chain? How the prototype works
<details>
  <summary>Answer</summary>
   
  https://medium.com/@chamikakasun/javascript-prototype-and-prototype-chain-explained-fdc2ec17dd04
   
</details>





Difference between these Object ways ?
```javascript
var obj1 = new Object();

var obj2 = object.create(null);

var obj3 = object.assign();

var obj4 = {};
```
What is a deep copy and shallow copy?

How to deep copy and object of objects?

What are the Array Methods that do not change the original Array?

How to restrict an object to iterateable ?

What is JS Design Patterns?

What is event bubbling and Capturing? What is the use of it?

How to differentiate b/w array and object in JS?

What are Implicit Objects in JavaScript?

What is the output?
```javascript
"1"+2+3, 2+3+"8" 
```
Is NaN == Nan ?

What are Closures? 

What is String Immutably?

How to make a promise to execute synchronously?

Difference Between JIT and AOT?

What is Shadow Cloning?

How does JS pass the parameter in function? By Value or Reference ?

What are first class functions ?

In which memory JavaScript variables are stored. Why do we use a heap?

What is Event loop in JavaScript

How to compare 2 Objects ?

Why undefined === null is false

What is Scope Chain?

Create a super keyword in JavaScript.

Difference between function constructor and normal function?



Is the prototype Can be null?





What are the generators and iterators?



Difference between promises and Generators?



How to stop promise in the middle?





What are various Array functions?



How to Implement Interfaces in JavaScript?



Diff between classical vs prototype inheritance ?



Why undefined === null is false


### JavaScript Puzzles

What is the output of the below code and why ?

```javascript
for (var i = 0; i < 5; i++) {
     setTimeout(function() { console.log(i); }, i * 1000 );
}
```

What is the output ?

```javascript
for (let i = 1; i < 5; i++) {

  setTimeout(function() { console.log(i); }, i * 1000);

}
```

What is the output ?

```javascript
function foo(i) {

  setTimeout(function() { console.log(i); }, i * 1000);

}
```

What is the output ?
```javascript
for (var i = 1; i < 5; ++i)

foo(i); 
```


What is the output of the following code and why ?

```javascript
console.log(1 + "2" + "2"); 
```


What is the output of the following code and why ?

```javascript
var x = 21;

var girl = function () {

    console.log(x);

    var x = 20;

};

girl ();
```


Create a function that can return the sum of all the params. 
```
https://codepen.io/tarunnagpal123/pen/ZEGbxZX?editors=0010
```


What is the output of the following code?

```
var x = 1;

x += typeof f;

console.log(x);
```


What are decorators in ES7?

Unclear Questions 
```
https://codepen.io/tarunnagpal123/pen/ZEGbxZX?editors=0010
```
