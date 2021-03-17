# CSS Transforms, Transitions, and Animations

## Transforms
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Transform Syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
One of the new properties in CSS3 is transform property.
This new property allows for new ways to position, size, and change elements.

The transform property can either be :

two dimensional or

three dimensional

Because the browser support for the transform property is still not great, vendor prefixes are used for best support.

* 2D Transforms Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
* 3D Transforms
  1. D Rotate: use three new transform values, including rotateX, rotateY, and rotateZ.
  2. 3D Scale: the scaleZ three-dimensional transform elements may be scaled on the z axis.
  3. 3D Translate: Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.
  3. 3D Skew: Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale.
* Perspective
* Combination between Transforms
* Styling Transforms

##  Transitions & Animations

<img hight="50" width="600" src="https://bardotbrush.com/wp-content/uploads/2019/04/Untitled_Artwork-2.gif">


One evolution with CSS3 was the ability to write behaviors for transitions and animations

With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

There are four transition related properties in total, including:

* transition-property
* transition-duration
* transition-timing-function
* transition-delay
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.

## Perspective
The perspective of an element can be set in two different ways. One way includes using the perspective value within the transform property on individual elements, while the other includes using the perspective property on the parent element residing over child elements being transformed.

## Animations
When multiple transitions are required, the transition property becomes obsolete and the animation property becomes the focus. To set multiple points at which an element should transition, we use the @keyframes rule, which includes the animation name, any animation breakpoints, and the properties intended to be animated.
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
