# Shot Circuit Evaluation

If we want to check if a variable is truthey, and otherwise assign a default value if it is falsey, we can run the following code:

```
let x = '';
let y;

if (x) {
  y = x 
} else {
  y = 1
}  
console.log(y);
```
The code checks if variable x is truthy and assigns its value to x if so. When this condition returns as false, the variable y is then assigned a default value of 1, which is then printed.

This can be written in shorthand as:
```
let x = '';
let y = x || 1;

console.log(y);
```
Statements using the 'or' (||) operator check from left to right, so here the conditional first checks if x is truthy, and if not, assigns y a default value of 1.
