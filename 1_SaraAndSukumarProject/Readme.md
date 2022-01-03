/\*\*

-
-
- transform: translate(), scale(), rotate(), skew(). Two dimensional.
-
- \*\*/

.wrapper {
height: 300px;
width: 300px;
border: 1px dotted red;
margin: 0 auto;
}
.inner {
height: 300px;
width: 300px;
border: 1px solid black;
transform: rotate(30deg);
transform-origin: ;
}

/\*\*

-
-
-
- translate() => moves elements in horizontal or vertical directions.
- syntax: {
-          transform: translate(tx, ty)
-         }
-         {
-           transform: translate(tx)
-         }
-         tx -> length of translation along x-axis (px or percentage)
-         ty -> length of translation along y-axis (px or percentage)
-         {
-           transform: translateX(tx)
-         }
-         {
-           transform:translateY(ty)
-         }
-
-
- \*\*/

/\*\*

-
- scale -> resize elements in 2-D space
- Syntax: {
-           transform: scale()
-         }
- scale(sx, sy)
- scale(sx)
- scaleX(sx)
- scaleY(sy)
- sx -> The amount of resize of the element in horizontal direction - numbers(integer, decimals)
- sy -> The amount of resize of the element in vertical direction - numbers(integer, decimals)
-
- \*\*/

/\*\*

-
- rotate : Rotates elements in 2-D space
- Syntax: {
-           transform: rotation(a)
-         }
- a = angle
- => positive: clockwise rotation
- => negative: counter-clockwise rotation
- a = 360 degrees = 1 full rotation = 360 deg
- a = 400 gradians = 1 full rotation -> 400 grad
- a = 2 * pi radians = 2*3.14 = 6.28 radians = 1 full rotation => 6.28 rad
- a = 1 turn = 1 full rotation => 1 turn
-
- \*\*/

/\*\*

-
- skew : tilting elements in 2-D space
- Syntax: {
-           transform: skew(ax, ay)
-         }
-         {
-           transform: skew(ax)
-         }
-         {
-           transform: skew(ay)
-         }
-         {
-           transform: skewX(ax)
-         }
-         {
-           transform: skewY(ay)
-         }
- ax : The amount of angle to use to distort the element in horizontal direction
- ay : The amount of angle to use to distort the element in vertical direction
- ax, ay => degree, gradians, radian and turn.
-
- \*\*/

/\*\*

- transform-origin: Changing the transform origin. By default it is the center of the element
- Syntax: {
-           transform-origin: center center | 50% 50% (default)
-         }
- transform-origin: xAxis yAxis
- xAxis:left, right, top, bottom, center, percentage, length
- yAxis:left, right, top, bottom, center, percentage, length
-
-
-
-
- \*\*/
