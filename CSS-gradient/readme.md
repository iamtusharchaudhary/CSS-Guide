# CSS Gradients
CSS gradients let you display smooth transitions between two or more specified colors.

# Types:-
<ul>
  <li>Linear Gradients</li>
  <li>Radial Gradients</li>
  <li>Conic Gradients</li>
</ul>

# Linear Gradients
To create a linear gradient you must define at least two color stops. Color stops are the colors you want to render smooth transitions among. You can also set a starting point and a direction (or an angle) along with the gradient effect.

### Syntax:-
```
background-image: linear-gradient(direction, color-stop1, color-stop2, ...);
```

### Examples:-

> background-image: linear-gradient(tomato, gold);

> background-image: linear-gradient(to right, tomato, gold);

> background-image: linear-gradient(to bottom right, tomato, gold);

> background-image: linear-gradient(180deg, tomato, gold);

> background-image: linear-gradient(to right, rgba(255, 99, 71, 0.50), rgba(255, 215, 0, 0.50), rgba(65, 105, 225, 0.80), rgba(0, 128, 128, 0.70));

> background-image: repeating-linear-gradient(red, green 10%, yellow 20%);

# Radial Gradients
A radial gradient is defined by its center.
To create a radial gradient you must also define at least two color stops.

### Syntax:-
```
background-image: radial-gradient(shape size at position, start-color, ..., last-color);
```

### Examples:-

> background-image: radial-gradient(tomato, gold, green);

> background-image: radial-gradient(tomato 10%, gold 20%, green 50%);

> background-image: radial-gradient(circle, tomato, gold, green);

> background-image: radial-gradient(closest-side at 60% 50%, tomato, gold, green);

> background-image: repeating-radial-gradient(red, green 10%, yellow 20%);

# Conici Gradients
A conic gradient is a gradient with color transitions rotated around a center point.
To create a conic gradient you must define at least two colors.

### Syntax:-
```
background-image: conic-gradient([from angle] [at position,] color [degree], color [degree], ...);
```

### Examples:-

> background-image: conic-gradient(tomato, gold, green, royalblue);

> background-image: conic-gradient(tomato 45deg, gold 90deg, green 120deg, royalblue 250deg);

> background-image: conic-gradient(tomato, gold, green, royalblue);

> background-image: conic-gradient(red 0deg, red 90deg, teal 90deg, teal 180deg, red 180deg, red 270deg, royalblue 270deg);

> background-image: conic-gradient(from 90deg, rgba(255, 99, 71, 0.50), rgba(255, 215, 0, 0.50), rgba(65, 105, 225, 0.80), rgba(0, 128, 128, 0.70));

> background-image: conic-gradient(at 60% 40%, rgba(255, 99, 71, 0.50), rgba(255, 215, 0, 0.50), rgba(65, 105, 225, 0.80), rgba(0, 128, 128, 0.70));
