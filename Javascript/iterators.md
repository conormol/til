# Iterators

Iterator methods are bulit in to Javascript to make looping easier. The general syntax for an iterator method is as follows (including the array to be looped through., and the word'method' to be replaced by the iterator method syntax):

```
const myArray = [1, 2, 3, 4];

const myIteratorFunction = myArray.method(function(number) {
  return number > 2;
  });
```
This will return all numbers in the array greater than 2. Arrow notation can also be used: 
```
const myArray = [1, 2, 3, 4];

const myIteratorFunction = myArray.method(number => {
  return number > 2;
  });
```

Common iterators are as follows:

## forEach()
`forEach()` excutes the same code on each element of the array, but does not change the array. It returns `undefined`.

## map()
`map()` executes the same code on every element and returns an updated array with the new elements

## filter()
`filter()` checks through an array to see if each element meets a certain criteria and returns an array with elements that return `truthy`.

## findIndex()
`findIndex()` returns the index of the first element of an array that satisfies a certain condition. -1 is returned if no element satisfies the condition.

## reduce()
`reduce` iterates through elements and returns a single value

### Passing By Reference

Note that to pass an array by reference into the function, the parameter has to be declared as normal, instead of just referening the array itself:
```

const myIteratorFunction = arr => arr.method(number => 
  return number > 2;
  );
```
