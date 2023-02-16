# For Loops

## for 
For loop syntax is as follows:

```
for (i=0; i<x; i++) {
  // Perform action
}
```

## for...of

`for of` loops have a simpler syntax and allow us to concisely iterate throungh strings and arrays:

```
const myArray = ['item1', 'item2', 'item3']

for (const item of myArray) {    //creates constant variable item to cycle through array
  console.log(item)
}
```
