# Grid: Specifying Item Size

The size of each individual grid item can be specified using four properties or the related shorthands:

## grid-row

Specifies where a row item should start or end. This can be written as:
```
grid-row-start: 4;
grid-row-end: 6;
```
Or
```
grid-row: 4 / 6;
```
In this case, the item will cover rows 4 and 5, but not 6. This can also be written as:
```
grid-row: 4 / span 2;
```

## grid-column

Similar to grid-row, but to specify how many columns an item should span.


## grid-area

Shorthand to specify all of the above, in the form row-start / column-start / row-end / column-end:
```
grid-area: 4 / 3 / span 2 / span 2;
```
