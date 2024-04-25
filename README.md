# CSS-Guide

# What is CSS
CSS stands for Cascading Style Sheets.
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
CSS saves a lot of work. It can control the layout of multiple web pages all at once.
External stylesheets are stored in CSS files.<br>
CSS is the language we use to style an HTML document.

# CSS provides several methods to define the styles

> Inline Style Sheets

> Internal Style Sheets

> External Style Sheets


# Inline Style:-
This method allows you to apply styles directly to an HTML element using the style attribute. This method is useful for making quick, one-off style changes.
```
<h1 style="color: red;">This heading containt red color</h1>

```

# Internal Styles:-
This method allows you to define the styles within the section of your HTML document, using the <style> tag. This method is useful when you want to apply styles to a specific page only.
```
<head>
  <style>
    h1 {
      color: red;
    }
  </style>
</head>
```

# External Styles:-
In this method, you can define the styles in a separate CSS file, which is then linked to your HTML document using the tag. This method allows you to maintain consistent styles across multiple pages.
```
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```

# CSS File Code Like -->

```
/* Element Selector */
h1 {
  font-size: 24px;
}

/* Class Selector */
.myClass {
  background-color: #fff;
}

/* ID Selector */
#myId {
  border: 1px solid black;
}

```
