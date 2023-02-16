 # Factory Functions
 
 Factory functions return objects that can be reused to make multiple object instances.
 
 ```
 const myObject = (name, colour, shape) => {
  return {
    name: name,
    colour: colour,
    shape: shape
    }
  };
  ```
  
  The factory function can then be called to make an instance of that object:
  
  ```
  const objectOne = myObject(firstObject, blue, circle);
  ```

The shorthand for declaring a factory function is as follows: 

 ```
 const myObject = (name, colour, shape) => {
  return {
    name,
    colour,
    shape
    }
  };
  ```
