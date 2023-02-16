# The .this Keyword

When creating methods inside an object, the method does not automatically have access to the elements of that object. In order to access the elemnts, the `this` keyword has to be used.

```
const myObject: {
  colour: blue,
  shape: square,
  printColour() {
    console.log(this.colour)
    }
  }
```
Here, the `printColour()` method will have access to the `colour` element because the `this` keyword is being used.

Note that arrow notation cannot be used to declare the method if the `this` keyword is to be used.
  
