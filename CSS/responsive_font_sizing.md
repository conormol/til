# em and rem

em and rem are units of relative font sizing. em is best used when font size is to be kept consistent with or relative to nearby and parent elements. rem is best used when font size is to be kept consistent with or relative across all pages.

## em

em is a unit of font size which inherits the default size of an elements parent font. In the example below, all h1 elements that contained within a section element will have a font size of 15px (10px * 1.5).

```
section {
  font-size: 10px;
  }
  
secion h1 {
  font-size: 1.5em;
  }
```

## rem

rem is a unit of font size which inherits the default font size of the root (html) element. In the example below, all p elements will have a font size of 12px (10px * 1.2).

``` 
html {
  font-size: 10px;
  }

p {
  font-size: 1.2rem;
  }
```
