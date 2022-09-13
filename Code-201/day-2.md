# Reading notes class 2

### HTML FUNDAMENTALS

Most basic tags in html, <p> and <h1…>
Formatting is important in web sites because people parse too. They skim, we’re skimming right now, searching for relevant information.
It’s also an accessibility issue. Using text readers for folks.

- Semantics are intentional ways of using code. Not just making code look nice, but translate nicely when broken down into structure. This is why it's important.
- There are 6 levels of headings in HTML! Though it's not recommended you use all six varying degrees. You can use them spread out among pages, but try not to use more than three in a page.
- Footnotes & formulas! are some uses for subscript and superscript. Slowly realizing my last entry for notes was formatted pretty bad. Was not intentional about my code and used way too much subscript to try and utilize more stylings lol.
    - <sub> subscript, used for things like footnotes

    - <sup> superscript, used for things like scientific formulas
- For an <abbr> tag to work, you need to provide the full exapanding name of whatever you're abbreviating. 

* Other tags mentioned: *
<ul> </ul>
<ol></ol>
<li>…..
<em></em>emphasize
<strong></strong>also bold
<i> italic
<b>bold
<u>underline

### HTML ADVANCED TEXT FORMATTING

<dl> descriptive lists
<dt> descriptive term
<dd> descriptive definition

Ex. <dl>
		<dt></dt>
		<dd></dd>
	</dl>
        *you can also use nesting <dt> and <dd>*
If you’re using a quote from somewhere else, you can utilize block quote to signifiy this.
Ex. <blockquote cite=“link goes here”>

<p>Inline quotes, work in the same way as block quote, but utilize the <q> tag
Ex. Say you’re typing a paragraph and want to reference this cool article on Eater <q cite=“link goes here.”> and then you can continue typing your paragraph.</q></p>

<cite> tags only reference the title of what you’re wanting to mention. You could make that title a link though, using an anchor tag to take it to a webpage/email/other location.

<p> Say I wanted to markup <abbr title=“Hypertext Markup Language”>HTML</abbr>…


### HOW IS CSS STRUCTURED:

- What are selectors? 
    - They target html to apply styles to content. Selectors tell UNREAL
- Which components are the CSS declarations?
    - Inline styles; I think it’s like “color: blue”
- Which components are considered properties?
    - Human readable identifiers that indicate with style features you want to modify i.e. font, width, color.

### Things I'd like to know more about
- Feeling pretty solid with html, but am a little shaky about CSS. Spending more time this week reviewing the above questions and terms.
- I never thought I was very good at programming in Python, but learning fundamentals of JS has been unexpectedly helpful. Seeing lots of similarities between the two languages. Excited to learn more.
- Would also like to learn more about JS operators. Not super comfortable recognizing them yet.

### JAVASCRIPT BASICS “comments through events”

- What data type is a sequence of text enclosed in single quote marks?
    - String!
- List four types of Javascript operators
    - +, -, ===, ! (not) !== (does not equal)
- Describe a real world problem you could solve with a function.
    - Checking to see if you can afford something.
        - Function account (total,pending) {
            - Let result = total-pending;
            - Return result;
        - }

### MAKING DECISIONS IN YOUR CODE- CONDITIONALS

- An if statement checks a CONDITION and if it evaluates to TRUE, then the code block will execute.

**Basic if else syntax:**
	if (condition) {
		/*code to run if condition is true */
	} else {
	/* run some other code instead */
	}
- What is the use of an else if?
    - Else if is used if the condition for the if and else statement are both false. A third condition/ block of code. OR if you just want more than two possible conditions.
- List 3 different types of comparison operations.
    - Comparison operators are used to test the conditions of a code. 
        - === and == test if one value is identical to, or not identical to, another. 
        - < and > test if one value is greater than another
        - <= and >= tests if one value is less than or equal to, or greater than or equal to
- What is the difference between the logical operator && and ||? 
    - Logical operators are useful if you want to test multiple conditions without writing nested if…else statements. 
        - && “And” allows to chain together two or more expressions. All of them have to individually evaluate to true for the whole expression to return true.
        - || “or”; allows you to chain together two or more expressions that one or more of them have to ind. evaluate to true for the whole expression to be true.
- 
*** When testing booleans, any value that is not false, null, 0, or an empty string returns true when tested as a conditional statement. ***