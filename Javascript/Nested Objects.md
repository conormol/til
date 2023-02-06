# Nested Objects

Objects can be nested within other objects. Syntax:

```
let myObject {
  colourProperties: {
    colourOne: red,
    colourtwo: green,
    colourThree: purple
    },
  numberProperties: {
    numberOne: '10',
    numberTwo: '20',
    numberThree: 30
    }
 };
```

Operators can then be chained in order to access nested porperties:

```
myObject.colourProperties.colourOne;
```
