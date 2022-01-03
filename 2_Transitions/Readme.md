## Transition

transition:[property][duration][timing function][delay];

The above short hand property can be broken down into following individual properties

transition-property: This property can take many values. However we are interested in three values. They are
-none: No property will get transitions
-all: All transitionable properties will be transitioned.
-property name: defines a specific property. We can define multiple properties using comma separated property names.

transition-duration: This value can be seconds (3s) or milliseconds(1000ms). You can define multiple transition duration values for corresponding multiple transition properties using comma separated values.

transition-timing-function: The timing function can be defined in three ways. They are

- using predefined keywords: ease, ease-in, ease-out, ease-in-out, linear, step-start, step-end
- steps(): The transition is completed in steps.This function can be used with one parameter or two parameters.
  eg. step(n) or step(n, j)
  n: number of steps
  j: jump key word with a 'start' or 'end' value
- Cubic Bezier Curves:

transition-delay: This property is used to set time delay before transition starts. It is expressed either in seconds (eg 2s) or milli seconds(eg. 1000ms)

Transitionable Properties:https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties
