# minmax

the minmax function defines the minimum and maximum size of a grid element when the size of the grid container is increased or decreased. The height or width of the grid must be undefined for the to have an effect:

To give the second column a minimum and maximum width of 200px and 400px respectively:
 ```
 grid-template-columns: 100px minmax(200px, 400px)
 ```
