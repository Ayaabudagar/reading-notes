
# CSS Transforms, Transitions, and Animations

new ways to position and alter elements, the transform property comes in two different settings, 2D and 3D.

2D transforms
2D rotate (provides the apility to rotate an element from 0 to 360 degrees).
2D scale (allow you to change the appeared size of an element. the default scale value is 1, therefore any value between 0.99 and 0.01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger). **scale x **scale y
*2D translate (works a bit like that of relative positioning , pushing and pulling an element in different directions without interrupting the normal flow of the document). **translate x **translate y

2D skew(used to distort elements on the horizontal axis,vertical axis, or both). **skew x ** skew y

combining transforms ( for multi transforms to be used at once).
transforms origin (to change the default origin position, can accept one or two values).

perspective (can be set in two different ways . one way includes using the perspective value within the transform property on individual elements, while the other includes using the perspective property on the parent element residing over child elements being transformed).

perspective origin ( the same values used for the transform-origin property may also be used with the perspective-origin property, and maintain the same relationship to the element. The large difference between the two falls where the origin of a transform, while the origin of a perspective identifies the coordinates of the vanishing point of a transform).
3D transforms
3D rotate (x,y,z)
3D scale (x,y,z)
3D translate (x,y,z)
3D skew (x,y,z)




Transitions & Animations
Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

Transitions
There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay.

Transition Duration
The duration in which a transition takes place is set using the transition-duration property.

Transition Delay
On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property.

Animations
used to building out visual interactions from one state to another, and are perfect for these kinds of single state changes.

Animation Duration, Timing Function, & Delay
Once you have declared the animation-name property on an element, animations behave similarly to transitions. A timing function and delay can be declared using the animation-timing-function and animation-delay properties respectively.