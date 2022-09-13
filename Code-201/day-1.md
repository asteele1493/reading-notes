# *notes from class 01 readings* 

***How the Web works:***

Need to know clients & servers. Clients send requests to servers while servers send responses to clients. Reminds me of an API?

Clients can be web users, people with personal computers...
Servers are computers that store information, web pages, services...

***Terms to familiarize myself with:***
- TCP/IP: communication procedure, how data travels
- HTTP: (hypertext transfer protocol) defines how info travels

***Parsing happens top down***
- this is why most JS is written towards the bottom of a web page. The page needs to parse through HTML and CSS first, and will then render JS. 

***Javascript basics***
- Variables store values
    - They can be varying data types (numbers, strings, booleans)
    - Semicolons dictate when a statement ends.
    - JS is case sensitive!!!

## Things I want to know more about: 

- Are lists the same thing as arrays? Seeing similarities from Python. 
- Difference between <section> and <br>

1. Compose a short poem describing how HTTP sends data between computers
        <sub>As a client myself, with questions abound, I send a[n] (HTTP) request, and receive answers profound. With my laptop as client, I reach out to a server, the IP address noted, I pocket approval (200) and data with fervor.</sub>
2. Describe how HTML, CSS, and JS files are ‘parsed’ in the browser.
        <sub>HTML is always parsed first. Any tags indicating CSS code is parsed second with JavaScript parsed third. Top to bottom; think like web browser. Reads line by line. If html references a css of js file, it goes to that section. JS is linked at bottom of body to allow rest of page to load.</sub>
3. How can you find images to add to a Website?
        <sub>Google Image search with a filter on for only showing images with usage rights suitable for the project.</sub>
4. How do you create a string vs a number in JavaScript?
        <sub>Strings are always contained in quotes. Numbers don’t utilize the single quotes. They’re a data type on their own.</sub>
5. What is a variable and why are they important in JavaScript?
        <sub>I think of variables as the building blocks of writing code. They contain varying data types that allow you to do different things and represent different statements/ideas.</sub> 

***Introduction to HTML***
1. What is an HTML attribute?
    <sub> An HTML attribute is extra. It gives a little more info about an element. Does it lead to a web page? Does it describe where the content leads to, like an email address or a different tab?  
2. Describe the Anatomy of an HTMl element.
    <sub> An HTML element is content surrounded by an opening and closing tag (in most cases). The entire block of code is called an element. Though this does feel very straightforward, this is directly referenced in the following source: *** https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started ***
3. What is the Difference between <article> and <section> element tags?
    <sub> Section tags define your document-- they designate sections (introduction, about section, contact section), whereas articles can be standalone documents. Makes me think of a newspaper article or blog post. 
4. What Elements does a “typical” website include?
    <sub>The reading on mdm web docs (https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure) mentioned basic webpage layout including a header, nav bar, main content, sidebar, and footer. Going further, you could have differing headers to separate parts of the page (h1, h2, etc.), paragraphs (p), or articles, among others.</sub>
5. How does metadata influence Search Engine Optimization?
    <sub> Metadata are short, defining characteristics of a webpage. A lil synopsis. The keywords you use can make or break your website in terms of hits when someone goes to search for it.</sub>
6. How is the <meta> HTML tag used when specifying metadata?
    <sub> I'm a little confused about this question. The meta tag specifies descriptors or items of relevance to the webpage. It can be used to give brief descriptions and go as far as to list off the name of the author, languages presented, and content intention. I'll come back to this question.</sub>

    ***Miscellaneous***
    1. What is the first step to designing a Website?
        <sub> The first step is to figure out your intent-- what is the website going to be about! If there are too many ideas or directions, it doesn't matter if the code is good, the site itself won't make sense. I learned this process is called project ideation. </sub>
    2. What is the most important question to answer when designing a Website?
        <sub> A website is a big project to undertake, so identifying what your goals are and how you plan to achieve them are important questions to resolve. Creating a plan and asking yourself how your workflow manifests itself, I think, is the most important question.</sub>

    ***Semantics***
    1. Why should you use an <h1> element over a <span> element to display a top level heading?
        <sub> The span tag has no semantic value. Using the h1 tag will create a heading, while the span tag will only make the content appear to be a heading.</sub>
    2. What are the benefits of using semantic tags in our HTML?
        <sub> Using semantic tags creates meaningful code. Being intentional about the code we use can make our content more accessible to those who may be differently abled. It can also help our content become more popular by optimizing it's search results. </sub>
    ***What is JavaScript***
    1. Describe 2 things that require JavaScript in the Browser?
        <sub> API's! API's allow two pieces of technology to talk to each other. Like when you use Spotify or Twitter. Google Maps also utilizes a GeoAPI to visualize data in regards to location. </sub>
    2. How can you add JavaScript to an HTML document?
        <sub> By using the script element! Same idea, with an opening and closing tag around the block of code. </sub>