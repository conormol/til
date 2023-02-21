# Objects: Privacy

In order to make an element of an object private (i.e remove the ability to easily access the element), the elemnt can be given an underscore prefix.

```
const myObject {
  colour: blue,
  _shape: red
  }
```

in the above code, `_shape` cannot be easily accessed because it has been made private.

## Getter Functions

To access a private element outside of the object, a getter method has to be used. Note that the `this` keyword must still be included to access it within the object:

``` 
const myObject {
  colour: blue",
  _shape: "circle",
  get printShape() {
    console.log(this._shape);
  }
```
The getter function can then be called outside the object to return the private element. Note that the getter method does not need brackets after it when called:
```
myObject(printShape);
```

## Setter Functions

Setter methods can also be created to reassign existing values of an object outside the object:

```
const myObject {
  colour: "blue",
  _shape: "circle",
  set shape(newShape) {
    this._shape = newShape;
  }
```
Then to set the value outside the object:
```
myObject.shape = "square";
```
