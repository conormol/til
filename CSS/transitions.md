# CSS Transitions

CSS transitions have 4 properties:

`transition-property`: The property that is being transitioned
`transition-duration`: The length of the transition
`transition-timing function`: The type of transition. Values include `ease`, `ease-in`, `ease-out`, `ease-in-out`, `linear`
`transition-delay`: The length of time before the transition takes place

This can also be written using the shorthand propert `transition`, where the vfour properties must be declaredin the folloing order:

`transition`: `transition-property` `transition-duration` `transition-timing function` `transition-delay`

For example:

```
transition: color 1s ease-in 0.5s;
```

Transitions can also be combined when the shorthand property is used. For example: 

```
transition: color 1s ease-in 0.5s, font-size 0.2s linear 100ms;
```

To target all properties being trasitioned, use `all` as a value for `transition-property`:
```
transition: all 1s ease-in 0.5s;
```
