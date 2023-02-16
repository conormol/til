JavaScript stores events as `event` objects with their related data and funtionalities as properties and methods. when an event is triggered, the event object can be passed as an argument to the event handler function
```
let element = document.getElementById('element');

let displayType = function(event) {
  console.log(event.type);
  };
 

element.addEventListener('click', displayType);

```
In the above example the `displayType` event handler function prints the name of the event to the console. The `.type` propertiy is a property of the `event` object. Other examples of event object properties are:

- `.target` references the element that the event is registered to
- `.timeStamp` accesses the number of milliseconds passed since the document was loaded and the event was triggered
