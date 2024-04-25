# CSS Selectors
<ul>
  <li>A CSS selector selects the HTML element(s) you want to style.</li>
  <li>CSS selectors are used to select and apply styles to specific HTML elements.</li>
</ul>

## Element Selector:-
 This selector targets all instances of a specific HTML element on the page.
 ```
 h {
  color: blue;
}
```

## Class Selector:-
This selector targets all elements that have a specific class attribute value.
```
.text {
  text-align:center;
}
```

# ID Selector:-
This selector targets a single element with a specific ID attribute value.
```
#text {
  background-color: royalblue;
}
```

# Descendant Selector:-
This selector targets elements that are descendants of a specific parent element.
```
.parentElement li {
  list-style: none;
}
```

# Attribute Selector:-
This selector targets elements with a specific attribute value.
```
input[type="text"] {
  color:red;
}
```

# Universal Selector:-
The universal selector (*) selects all HTML elements on the page.
```
* {
  text-align: center;
  color: blue;
}
```
