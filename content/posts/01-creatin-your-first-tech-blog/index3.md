---
title: Variable hoisting
author: Rakesh Baghel
date: 2019-09-08
hero: ./images/d.png
---

# Variable hoisting in Javascript
***
Hoisting is JavaScript default behavior to moving declaration on the top .Variable can used before its declaration.

 To understand this , first we need to understand of hoist meaning , hoist means "raise(something) by means like bubbles which are always on top. now we can relate hoisting with JavaScript. JavaScript interpreter moves all declaration on the top at run time.

 It is best practice to declare all variable at the top of their respective scopes. 

 But JavaScript does not allow variable used before its declaration in "use strict" mode.

## how we see the code 

``` javascript
a=10;
console.log(a);
var a;
```
## how javascript see

```javascript 
var a;
a=10;
console.log(a);

```

so basically only variables are hoisted to the top,not variable initialization.
lets understand hoisting with another example...

## how we see the code

```javascript 
var a= 10;
console.log(a + "" + b);
var b= 20;

```
## how javascript see

```javascript 
var a;
a= 10;
var b;
console.log(a + "" + b);
b=20;
```
here, the output is ...
```javascript
console.log(a + "" + b);
//10 undefined
```
here , if we assigning the value of b after console thats why the value of b is undefined.but we assign the value of a before console so it displays the value of a.