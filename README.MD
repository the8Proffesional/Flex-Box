<center><h1>FlexBox</h1></center>

## Parent

* Make a container flexbox

```css
.ClassName {
    display : flex | inline-flex;
}
```
* Flex Direction
```css
.ClassName {
    flex-direction: row (default) | column | row-reverse | column-reverse;
}
```

* Flex wrap
```css
.ClassName {
    flex-wrap: nowrap (default) | wrap | wrap-reverse | column-reverse;
}
```

* Shurthand Flex direction flex wrap
```css
.ClassName {
    flex-flow: row (default) | column | row-reverse | column-reverse || nowrap (default) | wrap | wrap-reverse | column-reverse;
}
```

* Justify content across main axis
```css
.ClassName {
    justify-content: flex-start (default) | center | flex-end | center | space-around | space-between | space-evenly;
}
```

* Align items
```css
.ClassName {
    align-items: stretch (default) | flex-start | flex-end | center | base-line;
}
```
whene flex-wrap is set to wrap or wrap-reverse
```css
.ClassName {
    align-content: normal (default) | flex-start | center | flex-end | center | space-around | space-between | space-evenly | stretch;
}
```
* Gap between elements
```css
.ClassName {
    gap : value value;
    row-gap: value;
    column-gap: value;
}
```

## Children

* Order
```css
.ChildClassName {
    order: 0 (default) number;
}
```
* Flex-grow
```css
.ChildClassName {
    flex-grow: 1 (default) number;
}
```
* Flex-shrink
```css
.ChildClassName {
    flex-shrink: 1 (default) number;
}
```
* Flex-basis
```css
.ChildClassName {
    flex-basis: auto (default) value;
}
```
* Flex
```css
.ChildClassName {
    flex: none | [ <flex-grow> <flex-shrink> <flex-basis> ];
}
```

* Flex align
```css
.ChildClassName {
    align-self: auto | flex-start | flex-end | center | baseline | stretch;
}
}
```