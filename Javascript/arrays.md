# Arrays

## Creating Arrays

Arrays are created with Square Brackets. Each item is at a numbered position, starting at 0.
```
let myArray = ['item1', 'item2', 'item3'];
```

## Accessing and Changing Items

Items can be accessed by referencing its index:
```
console.log(myArray[0]); // Will return item1
```

Items can also be reassigned
```
myArray[0] = 'itemA'; // Will change item1 to itemA
```

## Length Property

The number of items in an array can be checked using the .length property:
```
console.log(myArray.length); // Will return the number of items in the array
```
## Methods

Methods such as `.slice()`, `.shift()`, `.push()`, `.pop()`, `.unshift()` can be performed to mutate the array.
Variables can be mutated even if they are declared `const`, however items cannot be reassigned unless the are declared `let`.
Arrays mutated inside a function will remain changed outside the function.

## Nesting

Arrays can be nested inside other arrays:
```
let myArray = [['item1', 'item2'], ['item3', 'item4']];
```
To Access one item, indices can be chained using bracket notation:
```
console.log(myArray[1][0]); // Will Return item3
```




