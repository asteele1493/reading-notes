# Flexbox & HTML

## [Flexbox from MDN docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

*a note: read up to "Flex-Flow Shorthand"*

- What are some advantages of using flexbox over float?
  -Flexbox allows for a more flexible layout. Since your children elements inherit flex as a property from their parent element (or container), your sections can wrap along the page and adjust their sizing as your page changes dimensions. The possibility of children elements overflowing their container elements and breaking out of their layout is no longer an issue. 

- How does this topic connect with your long term goals?
  -My long term goals include becoming more comfortable with CSS and designing web pages. I don't feel like it's my strong suit at all. Most of the web pages I build look like they came out of a 2000's web capsule. Being able to implement flex layouts in my programming will (I hope) make any web page I create look and feel better.

## [Flexbox from webdev resource](https://web.dev/learn/css/flexbox/)

- Flexbox is designed for one-dimensional content. Explain what this means.
  -The sentence that stuck with me the most in this article's introduction is that flexbox "...excels at taking a bunch of items which have different sizes, and returning the best layout for those items." Providing flexible boundaries seem like a reasonable thing to implement in web pages and applications. Mostly thinking in terms of mobile applications or screens that may need an adjusted frame. 

- Explain the difference between the main axis and cross axis.
  -The podcast associated with this page did a great job of explaining this. The main axis goes from left to right. It is associated with the 'row' your layout may encompass. The main axis is set by the `<flex-direction>` property; if the property is set to `row`, it is along the main axis. The cross axis on the other hand runs perpendicular to the main axis. It is a column. If `<flex-direction>` is set to `column`, the cross axis runs along the column.

- How can using certain properties of flexbox negatively impact accessibility?
 - When using flexbox, you could reorder the visual display and make it different than what the HTML says. A screen reader will read out the logical order.

- *When using flexbox, you need to declare the usage of flex formatting. You must change the value of the display property to flex.*

  `.container {
    display: flex;
  }`
