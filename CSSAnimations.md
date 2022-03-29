# CSS Transforms, Transitions, and Animations.  

---  

## Transforms  

The transform property allows you to have alternate ways to size, position, and change elements.  

The property comes in two different setting, two dimensional and three dimensional.  

Unfortunately browser support for the transform property isn't great. vendor prefixes are reccomended to gain the best support accross all browsers.  

The transform property accepts several different values, including.  

- **Rotate**- Provides the ability to rotate an element from 0 to 360 degrees.  
- **Scale**- Allows you to change the appeared size of an element.  
- **Translate**- Using this value will change the position of an element on the axis. translateX for horizontal. translateY for vertical.  
- **Skew**- Distorts elements on the desired axis or both axis.  

The transform origin is the dead center of an element, to change this the *transform*-origin property may be used.  

In order for three dimensional transforms to work all of the elements need a perspective from wich to transform. This will need a depth value as well set as none or a length measurement. The higher the number the farther away the perspective appears.  

## Transitions and Animations  

With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs. Animations allow the appearance and behavior of an element to be altered in multiple keyframes.  

**Transitions**  

For a transition to take place there needs to be a *change of state*. The easiest way to determine the style for different states would be to use the following psuedo classes.  

- :hover
- :focus
- :active
- :target

There are four transition related propeties in total.  

- *transition-property*. Determines what properties will be altered in conjunction with the other transitional properties.
- *transition-duration*. The duration in which a transition takes place.
- *transition-timing*. Sets the speed in which the transition will move.
- *transition-delay*.  Sets a time value to determine how long the transition should be stalled.  

You can shorthand with just the transition property itself. 

**Animations**  

Animations pick up where transitions leave off. Sometimes you need a bit more control as apposed to just visual interactions from one state to another. 

To set multiple points at which an element should undergo a transition, you need to use the @keyframes rule. This includes the animation name, breakpoints and the properties intended to be animated.  

You then need to use the *animation-name* property to declare a name, and apply it to the element in which you want the animation to be applied to.  

Animations behave similarily to transitions in the fact that they include a duration, timing function, and delay if desired.  

By default, animations run their cycle once from beginning to end and then stop. To repeat any animation the *animation-iteration-count* property is used.  

You may also declare the direction an animation completes using the *animation-direction* property. Values include.  

- normal
- reverse
- alternate
- alternate reverse  

To allow an animation to be played or paused you need to use the *animation-play-state* property. Using the running and paused keyword values respectively.  

The *animation-fill-mode* property determines how an element should be styled either before or after an animation is run. This accepts four keyword values.  

- none
- forwards
- backwards
- both

Animations, just like transitions can be written in shorthand.  


