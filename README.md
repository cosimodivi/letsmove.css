# Let's Move.css

**Let's Move** groups together a set of CSS animations so you don't have
to use JavaScript or write the CSS code by yourself.

## Why choose Let's Move?

You **shouldn't** choose Let's Move. It's just an attempt to make practice 
with CSS' `@keyframes` feature and create CSS animations by myself.

You should absolutely go for [Animate.css](https://github.com/daneden/animate.css): 
it's _more reliable_, _cross-browser_ and _developed better_.

## Getting Started

First, add the `lets-move` class to your element and then specify the 
animation's class:

```html
<div class="lets-move fade-in">
  <p>Hello, world!</p>
</div>
```

You can change the animation's length _up to_ 10 seconds:

```html
<div class="lets-move fade-in-3s">
  <p>You'll see me by 3 seconds</p>
</div>

<div class="lets-move fade-in-6s">
  <p>My animation takes longer</p>
</div>
```

You can also repeat an animation forever (please don't):

```html
<div class="lets-move pulse infinite">
  <p>I'll become boring soon</p>
</div>
```

## Available effects

- **Fade effect:** `fade-in`
- **Pulse effect:** `pulse`
