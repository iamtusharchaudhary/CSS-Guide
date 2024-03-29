# CSS-Guide

# What is CSS
CSS stands for Cascading Style Sheets.
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
CSS saves a lot of work. It can control the layout of multiple web pages all at once.
External stylesheets are stored in CSS files.<br>
CSS is the language we use to style an HTML document.

# CSS Backgrounds 
The CSS background properties are used to add background effects for elements.
1. background-color
2. background-image
3. background-repeat
4. background-attachment
5. background-position

# CSS Borders
The CSS border properties allow you to specify the style, width, and color of an element's border.

CSS Border Style
The border-style property specifies what kind of border to display.

The following values are allowed:

1. dotted - Defines a dotted border
2. dashed - Defines a dashed border
3. solid - Defines a solid border
4. double - Defines a double border
5. groove - Defines a 3D grooved border. The effect depends on the border-color value
6. ridge - Defines a 3D ridged border. The effect depends on the border-color value
7. inset - Defines a 3D inset border. The effect depends on the border-color value
8. outset - Defines a 3D outset border. The effect depends on the border-color value
9. none - Defines no border
10. hidden - Defines a hidden border

# CSS Margins
The CSS margin properties are used to create space around elements, outside of any defined borders.
With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).
# CSS has properties for specifying the margin for each side of an element:
1. margin-top
2. margin-right
3. margin-bottom
4. margin-left

# Example:-
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}

# Margin-Shorthand Property:-
If the margin property has four values:-

=> margin: 25px 50px 75px 100px;

  1. top margin is 25px
  2. right margin is 50px
  3. bottom margin is 75px
  4. left margin is 100px

# Example:-
Use the margin shorthand property with four values:-
p {
  margin: 25px 50px 75px 100px;
}
