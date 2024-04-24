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
