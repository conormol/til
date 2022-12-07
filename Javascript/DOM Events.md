# Dom Events

## Add Event Listener

Events can be registered to DOM elements using addEventListener. The addEventListener method takes two arguments: an event type and an event handler function. When an event is triggered on the event target, the registered event handler function executes.
```
let element = document.getElementbyId('element');

function turnBlue() {
  element.style.backgroundColor = 'blue';
  };
  
document.addEventListener('click', turnblue);
```

In the above example, the function `turnBlue()` is the event handler function, and, turns the background of the event target (the variable 'element')  blue. The `addEventListener` method then takes two arguments: The event type `'click'` and the event handler function, and triggers the event.
