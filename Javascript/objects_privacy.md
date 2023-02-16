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

To access a private element, a getter method has to be used. Note that the `this` keyword must still be included:

``` 
const myObject {
  colour: blue,
  _shape: red
  get printShape() {
    console.log(this._shape);
  }
```

## Setter Functions

Setter methods can also be created to reassign existing values of an object

```
const myObject {
  colour: blue,
  _shape: red
  set shape(newShape) {
    this._shape = newShape;
  }
```
