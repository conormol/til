# Truthy and Falsy

Truthy and Falsy are values that indicate whether or not a variable has been assigned a value. A conditional statement is 'truthy' if the variable in question has been assigned a value, and is falsy if the variable is undefined:

A:
```
let x = 1;

if (x) {
  console.log('x has value')
 } else {
  console.log('x does not have vale')
 }
 ```
 The output here will be 'x has value'. The statement is truthy, because the variable is defined, regardless of what the variable has been defined as.
 
 B:
```
let x ;
 
if (x) {
  console.log('x has value')
 } else {
  console.log('x does not have vale')
 }
 ```
 The output here will be 'x does not have value', as the variable is undefined
