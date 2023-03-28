# The `Error` Function

The `Error` function can be used to create an error object for errors that aren't covered by Javascript built-in errors. The function takes in an argument of a string which becomes the value of the error's `message` property. For example:
```
console.log(Error("Your password is too weak"));
```

# The `Throw` Keyword

The `Error` function alone will not cause the program stop due to an error. Placing the `Throw` keyword before the error will, however.
```
throw Error("This will stop the program")
```

# try...catch

The `try...catch` statement is used to anticipate and handle errors. The syntax is as follows:
```
try {
  throw Error("This is an error")
} catch (e) {
  console.log(e);
}
```
The code inside the first set of curly brackets is known as the `try` block, which is code that we anticipate might throw an error. If an error is thrown, the error message logged gets pushed to the `catch` block, where `e` represents the thrown error. The error message is then logged to the console, however te program can conitinue to run once the `try...catch` block has been executed.
