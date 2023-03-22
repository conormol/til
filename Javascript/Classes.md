# Classes

Classes are reusable templates for producing similar objects.

A class must contain `constructor()` method. This method is called each time a new instance of the class is created. Note also in the example below that class names by convention are capitalized and CamelCase.
```
class Food {
  constuctor(name, type) {
    this._name = name;
    this._type = type;
    }
}
```

Above, the constructor method takes two arguments, `name` and `type`. Inside the method, the `this` keyword is used, which refers to the instance of the class. An instance of the class can be created as follows: 
```
const apple = new Food('apple', 'fruit')
```
This stores an instance of the class into a variable named `apple`, passing in the strings `apple` and `fruit` into the arguments `name` and `type`.

## Class Methods

