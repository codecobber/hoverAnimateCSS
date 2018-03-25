# hoverAnimateCSS
Using animate css with jquery and mouseleave mouseenter.

Animate css is a superb library of animation effects however I needed to use the effects with hover.

Jquery made the process really simple.

--------------------------------------

I added a data attribute (data-animate) to the element I needed to animated (eg paragraph), this holds the class names that we need to run animate css. Though nothing happens while the data stays as an attribute.

Next I stated the classes required as precified within the animateCss docs. (data-animate="animated infinite bounce")

We also require the class that jquery searches for so as to activate the animation effect, in this case I used 'hovMe' though you can use whatever you like.

When hovering over an element that posseses the class 'hovMe', jquery then finds the data attributes of that element and adds them to the class of that element. Now the animation effect takes effect.

When the mouse leaves the element the reverse occures and the relevant classes that were added on hover are now removed from the class of the element.

Simple really!
