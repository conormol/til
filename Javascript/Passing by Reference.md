# Passing by Reference

In order to pass a variable assigned to an object into a function as an argument, the object must be passed by reference.

```
let myObject = {
  propertyOne: blue,
  propertyTwo: red
  };
  
  
let newColour = objectVar => {
  objectVar.propertyOne = 'green'
  }
  
newColour(myObject);
```

In the code above, the function ``newColour`` is using dot notation to mutate the variable passed into it. When the variable passed in is myObject, the property ``propertyOne`` changes to ``green``.
