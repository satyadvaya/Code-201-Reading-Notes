# External Article
## _CSS Transforms_
### Transform Syntax
- The `transform` property includes multiple vendor prefixes to gain the best support across all browsers. The un-prefixed declaration comes last to overwrite the prefixed versions, should a browser fully support the transform property.
### 2D Transforms
- *2D Rotate*
    - The `rotate` value provides the ability to rotate an element from 0 to 360 degrees.
- *2D Scale*
    - Using the `scale` value within the transform property allows you to change the appeared size of an element.
- *2D Translate*
    - The `translate` value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
- *2D Skew*
    - The `skew` value is used to distort elements on the horizontal axis, vertical axis, or both.
### Combining Transforms
- To combine transforms, list the transform values within the transform property one after the other without the use of commas.
### Transform Origin
- The default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the `transform-origin` property may be used.
### Perspective
- In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a _vanishing point_, similar to that which can be seen in three-dimensional drawings.
- The perspective of an element can be set in two different ways. One way includes using the `perspective` value within the `transform` property on individual elements, while the other includes using the `perspective` property on the parent element residing over child elements being transformed.
    - _Perspective Depth Value_
    - _Perspective Origin_
### 3D Transforms
- Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.
    - _2D Rotate_
    - _3D Scale_
    - _3D Translate_
    - _3D Skew_
    - _Shorthand 3D Transforms_
### Transform Style
- On occasion three-dimensional transforms will be applied on an element that is nested within a parent element which is also being transformed. In this event, the nested, transformed elements will not appear in their own three-dimensional space. To allow nested elements to transform in their own three-dimensional plane use the `transform-style` property with the `preserve-3d` value.
### Backface Visibility
- When working with three-dimensional transforms, elements will occasionally be transformed in a way that causes them to face away from the screen. This may be caused by setting the `rotateY(180deg)` value for example. By default these elements are shown from the back. So if you prefer not to see these elements at all, set the `backface-visibility` property to hidden, and you will hide the element whenever it is facing away from the screen.
- The other value to `backface-visibility` is `visible` which is the default value, always displaying an element, no matter which direction it faces.

# External Article
## _Transitions & Animations_
- With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.
- Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.
### Transitions
- Vendor Prefixes
- Transitional Property
- Transition Duration
- Transition Timing
- Transition Delay
### Shorthand Transitions
- Using the `transition` value alone, you can set every transition value in the order of `transition-property`, `transition-duration`, `transition-timing-function`, and lastly `transition-delay`. Do not use commas with these values unless you are identifying numerous transitions.
- To set numerous transitions at once, set each individual group of transition values, then use a comma to separate each additional group of transition values.
### Animations
- *Animations Keyframes*
- *Animation Name*
- *Animation Duration, Timing Function, & Delay*
### Customizing Animations
- *Animation Iteration*
- *Animation Direction*
- *Animation Play State*
- *Animation Fill Mode*
### Shorthand Animations
- Fortunately animations, just like transitions, can be written out in a shorthand format.

# External Article
## _8 Simple CSS3 Transitions That Will Wow Your Users_
- Fade in
- Change color
- Grow & Shrink
- Rotate elements
- Square to circle
- 3D shadow
- Swing
- Inset border