# **HTML Images, CSS Color & Text**

## HTML Media readings

### [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

- Images are added to webpages using the `<img>` tag. This is an empty tag that requires at least one attribute to run. This is typically the *src* attribute. It points to where the image exists in the web or on your local machine.
-  
- What is a real world use case for the alt attribute being used in a website?
    - The `alt` attribute is essentially a synopsis of the image. A text description. This attribute comes in handy if your web page is having trouble loading the complete image, if a user is utilizing a screen reader to access the page, or for search engine optimization.
- Provide an example of when the figure element would be useful in an HTML document.
    - The figure element (to me) seems like self contained media. The site acknowledged above says the `<figure>` and  `<figcatption>` elements are semantic code-- they are created for web pages to clearly link the figure to the caption.

### [Image file type & format guide](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)

- There are seven main file formats for images on the web: APNG, AVIF, GIF, JPEG, PNG, SVG, and WebP. 

- Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
    - gif images were one of the first image types to be compatible with html. It's simple, widely used, and compatible with many programs. However, (I think) what really sets svg images apart are that they are scalable. When you try to adjust the size of a gif file, it becomes pixelated and obscured. Svg files make for a more seamless design.
- What image type would you use to display a screenshot on your website and why?
    - You should use a lossless format, unless you're okay with having a fuzzy image. The readings recommend Lossless WebP or PNG. 

## Learn CSS readings

### [Applying color to HTML elements using CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

- Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
    - Background colors are the colors behind what's on the page. Foreground colors are things like text, items you see when you first look at the web page.
- Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
    - I would start by choosing a base color and working in from that. I would also likely consult with a tool, like the Adobe color wheel, to find complementary colors since I don't feel super comfortable in creative design.

### [Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

- What should you consider when choosing fonts for an HTML document?
    - Something I never considered, but using a web safe font or font family to make sure the site is accessible across varying platforms.
- What do font-size, font-weight, and font-style do to HTML text elements?
    - Font-size changes the pixel size of the font. This can get tricky when you have nested text within html elements since font size is derived from parent elements. Font weight is essentially how bold your font is. Font style can be all of these things-- the font, the size, the italicization or bolding.
- Describe two ways you could add spacing around the characters displayed in an h1 element.
    - You could do letter or word spacing. Letter spacing increases or decreases the space around each letter, while word spacing does the same thing with whole words.

## Things I want to know more about

- I understand the concepts covered in this reading, but it feels like CSS is so expansive. Wondering exactly where to start to make web pages look clean and cohesive. 
- I'd like to learn more about color utilization. 
- Want to see more examples of image types.
