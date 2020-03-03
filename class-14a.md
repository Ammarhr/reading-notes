## Css Transform:
The transform property  is **css* property applies a 2D or 3D transformation to an element. This property allows you to manibulate elements.

-  **Rotate:** CSS function defines a transformation that rotates an element around a fixed point on the 2D plane, without deforming it.  ``rotate()``:
````
.rotated {
  transform: rotate(45deg); /* Equal to rotateZ(45deg) */
}
````
- **Scale:** CSS function defines a transformation that resizes an element on the 2D plane. use ``scale()`` for 2d and ``scale3d()`` for 3d:
````
.scaled {
  transform: scale(0.7); /* Equal to scaleX(0.7) scaleY(0.7) */
}
````
- **Skew**: CSS function defines a transformation that skews an element on the 2D plane ``skew()``:
````
.skewed {
  transform: skew(10deg); /* Equal to skewX(10deg) */
}
````
-----------------------
- **Transform-Origin**:property is used to change the position of the origin of transformation of an element.Ex:
````
transform-origin: top center;
transform-origin: 100% 30px;
transform-origin: 30px 60px;
transform-origin: center;
````
- **The Perspective** CSS function defines a transformation that sets the distance between the user and the z=0 plane, the perspective from which the viewer would be if the 2-dimensional interface were 3-dimensiona.``perspective()``:
````
.perspective-box-far {
  transform: perspective(9cm) rotateX(-15deg) rotateY(30deg);
}

.perspective-box-closer {
  transform: perspective(4cm) rotateX(-15deg) rotateY(30deg);
}
````

- **The Translate**: ``translate()`` CSS function repositions an element in the horizontal and/or vertical directions:
````
/* Single <length-percentage> values */
transform: translate(200px);
transform: translate(50%);

/* Double <length-percentage> values */
transform: translate(100px, 200px);
transform: translate(100px, 50%);
transform: translate(30%, 200px);
transform: translate(30%, 50%);
````
>>> **note:** there are the same functiond in 3d transform 
>>>
-------------------

## CSS Transitions:
CSS transitions allows you to change property values smoothly, over a given duration.
 Mouse over the element below to see a CSS transition effect:

- transition
- transition-delay
- transition-duration
- transition-property
- transition-timing-function

## To create a transition effect, you must specify two things:

the CSS property you want to add an effect to
the duration of the effect
>>> Note: If the duration part is not specified, the transition will have no effect, because the default value is 0.
>>>

#### Specify the Speed Curve of the Transition:
The ```transition-timing-function`` property specifies the speed curve of the transition effect.
The ``transition-timing-function`` property can have the following values:

- ``ease`` - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
- ``linear`` - specifies a transition effect with the same speed from start to end
- ``ease-in`` - specifies a transition effect with a slow start
- ``ease-out`` - specifies a transition effect with a slow end
- ``ease-in-out`` - specifies a transition effect with a slow start and end
- ``cubic-bezier(n,n,n,n)`` - lets you define your own values in a cubic-bezier function
-----------------

## CSS Animations:
CSS allows animation of HTML elements without using JavaScript or Flash! using :

- ``@keyframes``
- ``animation-name``
- ``animation-duration``
- ``animation-delay``
- ``animation-iteration-count``
- ``animation-direction``
- ``animation-timing-function``
- ``animation-fill-mode``
- ``animation``


