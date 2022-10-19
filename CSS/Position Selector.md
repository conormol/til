# Position selector

The Position determines the position of elements relative to one another

## Static
This is the default setting. The element will adhere to document flow and its position is determined by its position in the html file
```
position: static;
```

## Relative
The elemt is in a position relative to its dewfault value using offset properties. This has no effect if no offset values are in place.
```
position: relative;
```

## Fixed
The element is fixed/pinned to a specific spot on the page, regardless of scrolling. The user will always have access to this element
```
position: fixed;
```

## Absolute
Removes the element from the document flow and positions it to its closest parent element that is positioned with 'relative' or 'absolute'. It can then be positioned using the attributes 'Top', 'Bottom', 'Left' and 'Right'
```
position: absolute;
```

## Float
An element can be positioned to the far right or left of the page. For float to be used, the width of the element must be determined, otherwise it is assumed that the full width of the containing element should be used
```
float: left;
```

## Clear
Determines how an element should behave if it bumps in to another element. This is usually used in conjunction with 'float' elements to determine which side elements are allowed to float on
```
clear: right;
```
