## Why Forms?

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

The term 'form' has referred to a printed document that contains spaces for us to fill in information.

HTML borrows the concept of a form to refer to different elements that allow us to collect information rom visitors to our site.

The best known form on the web is probably the search box that sits right in the middle of Google's homepage it is enabling users to search, forms also allow users to perform other functions online.

**Form Controls**

There are several types of form controls:
* ADDING TEXT
* Making Choices
* Submitting Forms
* Uploading Files

Form Structure**

* Form controls live inside a <*form>* element. This element should always carry the action attribute and will usually have a method and id attribute too. 
* Every <*form>* element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted. 

* Forms can be sent using one of two methods: get or post. With the get method, the values from the form are added to the end of the URL specified in the action attribute.

**Text Input**

The _input_ element is used 
to create several different form 
controls. The value of the type
attribute determines what kind 
of input they will be creating.
* Text input: used for a single line of text such as email addressess and names.
* Password input: like a single line text bot but it masks the characters entered.
* Text area(multi line): for longer of text, such as messages and comments.


**Password Input**

type="password"
When the type attribute has a value of password it creates 
a text box that acts just like a 
single-line text input, except 
the characters are blocked out. 
They are hidden in this way so 
that if someone is looking over 
the user's shoulder, they cannot 
see sensitive data such as 
passwords.

**Text Area**
_textarea_
The _textarea_ element 
is used to create a mutli-line 
text input. Unlike other input 
elements this is not an empty 
element. It should therefore have 
an opening and a closing tag. 


## HTML5
HTML5 is introducing validation and
leaving the work to the browser.
Validation helps ensure the
user enters information in a
form that the server will be able
to understand when the form
is submitted.

HTML5 introduces new form
controls to standardize the
way that some information is
gathered.


### Lists, Tables and Forms

The **list-style-type** property
allows us to control the shape
or style of a bullet point (also known as a marker).
It can be used on rules that
apply to the <*ol>*, <*ul>*, and <*li>*
elements.

**Unordered Lists**

For an unordered list we can use
the following values:
* none
* disc
* circle
* square

We can specify an image to act
as a bullet point using the **list-style-image** property.
This property can be used on rules that apply to the <*ul>* and
<*li>* elements.

Lists are indented into the page
by default and the **list-style-position**
property indicates whether the marker should
appear on the inside or the
outside of the box containing the
main points.


Table Properties
You have already met several 
properties that are commonly 
used with tables. Here we will 
put them together in a single 
example using the following
1. width
 to set the width of the 
table
2. padding 
to set the space 
between the border of each table 
cell and its content
3. text-transform to convert the 
content of the table headers to 
uppercase
4. etter-spacing, font-size
to add additional styling to the 
content of the table headers
5. border-top, border-bottom
to set borders above and below 
the table headers
6. text-align to align the writing 
to the left of some table cells and 
to the right of the others
7. background-color to change 
the background color of the 
alternating table rows
8. :hover to highlight a table row 
when a user's mouse goes over it


## HOW EVENTS TRIGGER  JAVASCRIPT CODE 
When the user interacts with the HTML on a web page, there are three 
steps involved in getting it to trigger some JavaScript code. 
Together these steps are known as event handling. 

Select t he element 
node(s) you want the 
script to respond to. 

Indicate which event on 
the selected node(s) will 
trigger the response. 

State the code you want 
to run when the event 
occurs.
HTML EVENT HANDLER 
ATTRIBUTES (DO NOT USE) 

TRADITIONAL DOM 
EVENT HANDLERS
All modern browsers understand this way of creating an event handler, 
but you can only attach one function to each event handler. 

Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time 
but they are not supported in older browsers. 
**EVENT DELEGATION**

Creating event listeners for a lot of elements
can slow down a page, but event flow allows
us to listen for an event on a parent element.

BENEFITS OF EVENT DELEGATION
* WORKS WITH NEW
ELEMENTS
* SOLVES LIMITATIONS
WITH this KEYWORD
* SIMPLIFIES OUR
CODE

**CHANGING DEFAULT
BEHAVIOR**
The event object has methods that change:
the default behavior of an element and how
the element's ancestors respond to the event.

* preventDefault ()
* stopPropagation()
* USING BOTH METHODS

When calling a function, the event object's target property is the best
way to determine which element the event occurred on.

The *this KEYWORD*
The this keyword refers to the
owner of a function. On the right,
this refers to the element that
the event is on.

The HTML elements we can interact with, such as links and form
elements, can gain focus. These events fire when they gain or lose focus.

## Where events occur

The event object can tell us where the cursor saw positioned when an event was triggered.

Whenever elements are added to or removed from the DOM, its
structure changes. This change triggers a mutation event

The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.