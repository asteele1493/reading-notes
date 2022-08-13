# Audio, Video, and Images

## [Video & Audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.
- Describe the use of the src and controls attributes in the <video> element.
  - Very similar to `<img>` tags, `<video>` elements require a `src` component. Something that sets them apart are needing to also include controls. These controls enable a user to access video and audio playback. This is an accessibility issue for folks who experience epilepsy. `<video>` elements also include a paragraph, which I thought was a little funny. It makes sense though-- known as "fallback content", this text is viewed if the browser doesn't support the video file. This allows us to provide a fallback for older browsers.
- Something to note-- mobile browsers can sometimes support different file formats.
- Type attributes within `<source>` elements are useful in embedding AV files because they typically have the type of file format used. Browsers can read this and skip over what they can't play.

## [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

- How does Grid layout differ from Flex?
  - Flex utilizes one-dimensional flow (column or row), wheras grid layouts can be used to layout a page with rows and columns at the same time. It's a two-dimensional format.
- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe  these terms in a few sentences.
  - Grid container- The gird container is the parent element to all other grid elements in a webpage. 
  - Grid item- A grid item is any child element to the container. 
  - Grid line- These are the dividers that designate rows and columns in a webpage. 
- There are some similarities in properties to those seen in FlexBox (i.e. aligning items, space around, etc. ). 

## [Responsive Images](https://css-tricks.com/snippets/css/complete-guide-grid/)
- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
- Srcset and size attributes: srcset defines a set of images. It's tag is separated into three components: an image filename, a space, and the imag'es intrinsic width in pixels. Sizes defines a set of conditions for the image, such as screen width. These attributes tell the browser to look at the device's width, consider media condition, media query, and load the image in relation to the srcset list.
