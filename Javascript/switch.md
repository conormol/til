# The switch Keyword 

else/if statements can be written in shorthand using the switch keyword.

```
let x = 3;
```

```
if (x === 1) {
  console.log('x equals 1');
} else if (x===2) {
  console.log('x equals 2');
} else if (x===3) {
  console.log('x equals 3');
}
```
 
This can be re-written as:
```
switch (x) {
  case 1:
    console.log('console.log('x equals 1');
    break;
  case 2:
    console.log('console.log('x equals 2');
    break;
  case 3:
    console.log('console.log('x equals 3');
    break;
  default:
    console.log('x does not equal 1, 2, or 3);
    break;
}
```
Note that Case 1, Case 2, and Case 3 refer to whether x equals the number 1, 2, 3 or three, as opposed to numerical values assigned to each case. If, for example, we were trying to check if x was equal the strings Apple, Banana or Pear, it would read Case 'Apple', Case 'Banana', and Case 'Pear'.  

