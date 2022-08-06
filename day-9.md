# Forms & Events 

## [Your First Web Form] (https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

- *Web Forms* are a point of interaction between a user and a web site or applicaton. 
- These forms can be made up of one or more form controls (or widgets).

- Why are forms so important in web development?
  At a rudimentary level, I think it's because they allow users to interact with your web page.

  - When creating a form (whose layout you should take time to design and think through) there are a few items you should include in it's syntax. 
    - The `action` attribute defines the location, or URL, where the data submitted should be sent. 
    - The `method` attribute defintes with HTTP method to send the data with. Usually `get` or `post`.
  - You should use the `<form>` element to define where forms go.Using hooks will make them easier to use.
 - *Note* You cannot nest a form inside of another form.


### [How to structure a web form] (https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

- List 5 form elements and explain their importance.

- `<label>` : This is the formal element used to define a label for an HTML form widget.
- `<form>` : This element defines where a form begins.
- `<fieldset>`: This designates a group of widgets that share the same purpose, whether for styling or whatnot.
- `<legend>` : This element describes the purpose of the `<fieldset>` element.

## [Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

- How would you describe events to a non-technical friend?
  Events are things that happen when something happens to a computer program (someone interacts with it, clicks on a button, navigates to a different part of the page, and your program reacts to it.)
- An event handler is a reaction to an event. 
- When using the addEventListener() method, what 2 arguments will you need to provide?
  - The name of the event and a function to handle the event.
- Describe the event object. Why is the target within the event object useful?
  - The event object is a parameter inside an event. It is passed to event handlers to provide extra features and info. 
- What is the difference between event bubbling and event capturing?
  - Both are used to describe how the browser handles events targeted at nested elements. Bubbling is when the event bubbles up from the element that was selected. Event capturing is where a browser sees if the outermost element of a webpage has an event set, and runs it if so... I think?
