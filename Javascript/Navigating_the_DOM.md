# Navigating the DOM

## document

The document keyword grants access to the root of the DOM in Javascript

## query selector

the .queryselector() method allows us to access a specific element within CSS selectors
```
document.querySelector('h1');
```
## Selecting by ID

.getElementById() returns a single element
```
.getElementById('header-menu'); 
```
## Selecting by Class Name

.getElementsByClassName() returns an array of elements in the selected class. A single element can be called by its placement in the array, as in the example below
```
.getElementsByClassName('container')[2];
```
## Changing contents or style

.innerHTML() and .style() allow us to change the contents and style of an element respectively
```
document.getElementById('header-menu').innerHTML = 'New Menu Name';
```
```
document.getElementsbyClassName('container').style.backgroundColor = 'Blue'
```
Note that when changing style, camel case is used to identify what is being changed, as opposed to the hyphen standard in CSS (backgroundColor vs background-color)

## Create, Append, Remove

Elements can be created, added or removed using the following syntax
```
document.body.createElement('h1');
```
```
document.getElementById('header-menu').appendChild('Contact');
```
```
document.getElementById('header-menu').removeChild('Contact');
```

## Returning child and parent nodes

The .children property returns a list of of an elements child nodes, while .parent returns an elements closest parent node








