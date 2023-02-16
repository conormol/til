# Grid Rows and Columns

## grid-template-rows / grid-template-columns

Grids contain one row and column by default. To specify the number of rows and columns in a grid, use the property 'grid-template-rows' and 'grid-template-columns'. Then enter the size of each row or column, to create as many rows or columns as necessary.

The following will create three rows of 200px and three columns 300px and 400px:
```
grid-template-rows: 200px 200px 200px;
grid-template-columns: 300px 300px 300px;
```

This can be wirtten in short-hand as:
```
grid-template: 200px 200px 200px / 300px 300px 300px;
```

## grid-template (shorthand)

row and column sizes can be written in pixels (px), as a percentage of the overall grid size (%), or as a fraction of the remaining grid size (fr)


## repeat function

if multple rows or columns are required, the repeat function can be used. For example, four columns of 300px can be written as:
```
grid-template-columns: repeat(4, 300px);
```
