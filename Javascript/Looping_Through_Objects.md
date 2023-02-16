## Looping through Objects

Objects can be looped through using the ``for...in`` syntax. This will execute a block of code for each property in an object.

```
let myObject = {
  propertyTypes:  {
    colourProperties: {
      propertyOne: 'red',
      propertyTwo: 'green'
      },
    numberProperties: {
      propertyOne: '10',
      propertyTwo: '20'
      }
    }
};
 
 for (let property in myObject.propertyTypes) {
  console.log(`${property} : ${myObject.propertyTypes[property].propertyOne}`)
  }
```

The above code will return each occurance of property once in the form ``propertyOne: xxxxx``. Square brackets must be used to chain the variable ``property``.
