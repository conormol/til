# Inheritence

Inheritence involves creating a _parent_ class from which child classes can share or _inherit_ properties.

```
class Food {
  constructor(name, calories) {
    this._name = name;
    this._calories = calories;
  }
  
  get name() {
    return this._name;
  }
  
  get calories() {
    return this._calories;
  }
}
```
The `Food` class is a parent class, which will share the properties `name` and `calories` with child classes. A child class named `Apple` is shown below:
```
class Apple extends Food {
  constructor(name, calories, color) {
    super(name, calories)
    this._color = color;
```

The `super` keyword calls the constructor of the parent class. Note that the `super` method always be called before the `this` keyword can be used.
