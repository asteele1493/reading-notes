# Class 14a: CSS Transforms, Transitions, and Animations

## [CSS Tranforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

- What does a CSS transform allow the developer to do to an element?
  - The transform element allows a dev to revisit the size and position of elements. This can come in the form of a two-dimensional or three-dimensional transform.

  *The syntax for the transform property contains multiple prefixes to the actual transform element.* 
  - this is to ensure broswer compatibility across the web. The actual syntax looks something like this: 

- `div {
    -webkit-transform: scale(1.5);
    -moz-transform: scale(1.5);
    -o-transform: scale(1.5);
    transform: scale(1.5);
     }`

- 2D transforms operate on an x and y axis.
- 3D transforms use x, y, and z axes. 

- Provide an example of a transform and how you could see that being used on a website.
  - Some cool things transforms can do are scale an element to be bigger or smaller, change the perspective of an element, or even combine transforms to alter an element in more ways than one. I don't know if this is applicable at all, but seeing the transform perspective element legit reminded me of OG Star Wars introductions.

## [Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

- What does a CSS transition allow the developer to do to an element?
  - a CSS transition allows you to alter the state of an element upon an event occurring. Whenever a "state change" occurs.
    - Transitions have four properties involved in their syntax: transition-property, transition-duration, transition-timing-function, and transition-delay.
- How does a CSS animation differ from a CSS transition?
  - Animations are different in that they set multiple points of transition upon keyframes.
    - `@keyframes` is a rule you can use that includes animation name, breakpoints, and any other properties to be included.

## [Transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)

- What are some benefits to using CSS transitions on websites?
  - The article lists some of the reasons as transitions are exciting for users, but I think the reason I find the most important to be is that transitions encourage more engagement amongst viewers.
- How this topic fit in with your long-term goals?
  - From this reading, it sounds like many clients request transitions in web dev projects so these types of applications would be worthwhile to know. Also for the mere fact that they make users more likely to engage is a big selling point for me.
