##  on CSS Transforms
` https://learn.shayhowe.com/advanced-html-css/css-transforms/ ` 
### Transform Syntax
```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

```

## 2D Transforms
- Two-dimensional transforms work on the x and y axes, 
- Three-dimensional transforms work on both the x and y axes, as well as the z axis.
### 2D Rotate
- The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.

html 
```
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
```
css
```
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

```

## Transitions & Animations
### Transitions
- As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}

```
## Animations
- Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. 
- To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}

``` 