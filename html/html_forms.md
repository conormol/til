# HTML Forms

 A HTML form is used to allow users to input information and send it. A Html form is held within the following tags:
 ```
 <form>
 </form>
 ```
 
The `action` attribute determines where the information goes once it is submitted:
```
<form action="./example.html" method="POST">
</form>
```

There are various input types. It is good practice to label each input, and make reference to the input's id:
```
<label for="inputOne">This is the label for input one</label>
```

## Text Input

The syntax for a single line text input is as follows:
```
<input type="text" name="text-box" value="pre-filled text goes here" id="text-box-1">
```

## Password Input
The syntax for a password iput is similar, and renders a similar output to a text box, however the user's input will be hidden
```
<input type="password" name="user-password" id="user-password">
```

## Number Input
A number input is similar, and expects the user to select a number. Note that the default step is 1 and the min/max values are optional:
```
<input type="number" name="number-selector" id="number-selector" step="one" min="0" max="10">
```
## Range Input
A range input presents a user with a slider to select a variable number between a minimum and maximum:
```
<input type="range" name="range-selection" id="range-selection" step="1" min="0" max="10">
```

## Checkbox Input
A checkbox input presents the user with a number of checkboxes, of which the user can select more than one. There must be a label assosciated with each option:
```
<label for="option-one">Option 1</label>
<input type="checkbox" name="option-one" id="option-one">
<label for="option-two">Option 2</label>
<input type="checkbox" name="option-two" id="option-two">
<label for="option-three">Option 3</label>
<input type="checkbox" name="option-three" id="option-three">
```

## Radio Button Input
This is similar to a checkbox, however the user can only select one option:
```
<label for="option-one">Option 1</label>
<input type="radio" name="option-one" id="option-one">
<label for="option-two">Option 2</label>
<input type="radio" name="option-two" id="option-two">
<label for="option-three">Option 3</label>
<input type="radio" name="option-three" id="option-three">
```

## Dropdown List
Allows users to select an option from a dropdown menu. This uses a `select` tag as opposed to an `input` tag:
```
<select id="dropdown" name="options">
 <option value="option-one">Option One</option>
 <option value="option-two">Option Two</option>
 <option value="option-three">Option Three</option>
</select>
```

## Datalist
A datalist is similar to a dropdown, but allows users to type and filter options, and so is better when more options are available. It uses an input to create a text field, then presents filtered options when the user begins to type. The `list` attribute refers in the `input` tag refers to the datalist :
```
<input type="text" id="option-list" name="option-list" list="options"> 
 <datalist id="options" name="options">
  <option value="option-one">Option One</option>
  <option value="option-two">Option Two</option>
  <option value="option-three">Option Three</option>
 </datalist>
```

## Textarea element
A Textarea element is similar to a text box but allows for more than ne line of text. it uses the `textarea` tag:
```
<textarea id="user-input" name="user-input" rows="5" cols="30"><textarea>
```

## Submit Form
This creates a button to submit the information. The `value` attribute is the text contained within the button:
```
<input type="submit" value="Send">
```
