# How To Make A Style For Your Page?

![Styling](https://mk0architensx5k6hog9.kinstacdn.com/wp-content/uploads/architen_files/9def19dd14df38b83240be24c20dd464.jpg)

**let's start with the texts**

Each text is combined of Head and main paragraphs. in HTML to write a head you need to use H tags which consistes form 6 different levels from the most imprortent level to the least one. And to insirt these heads just open and close a _h_ tag with the specific number from 1-6.

To write a paragraph, open and close a _p_ tag and write anything you want in it. _b_ is to make a word bold, _i_ is to make it etlic _br_ is to start a new line and _hr_ to seperats between lines.

# Now How To make the Texts More lively?

![Design](https://miro.medium.com/max/6000/1*QHeR_o43WJdY5q91zOhmvA.png)

I believe you already know the answer. Of course it is CSS 

Will CSS as we mintioned, is used to make the degin of the web bage 

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. CSS Associates Style rules with HTML elements. For Ex: _p {font-family: Arial;}_

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one eclaration, each separated by a semi-colon. CSS Properties Affect How Elements Are Displayed. 
_h1, h2, h3 { font-family: Arial;  color: yellow;}_

 And to connect between the html and the css you need to provide a link in this formula
 _link href="css/nameOfFile.css" rel="stylesheet"_


 # We can't mintion the HTML&CSS without the JS

 so how does the JS wrote :)
## CREATING A BASIC JAVASCRIPT 

there are some data type you should deal with them 
1. NUMBERS Any type of numbers!
2. STRING ANY character on your keyboard!
3. BOOLEANS which is TRUE 1 & FULS 0

## WHAT IS A VARIABLE? 
A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs. 
to declear variables just hit var NAME;
you can assign thim using **=** to any datatype

## STATEMENTS 
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 
_JAVASCRIPT IS CASE SENSITIVE_
_STATEMENTS ARE INSTRUCTIONS AND EACH ONE STARTS ON A NEW LINE_
_STATEMENTS CAN BE ORGANIZED INTO CODE BLOCKS_

**SWITCH STATEMENTS**

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.
switch(level){
case'One':title='Level1';
break;
case'Two':title='Level2';
break;
case'Three':title='Level 3' ;
break ;
default:title= 'Test';
break; 

## COMMENTS 
You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.
EX on MULTI-LINE COMM ENTS 
/* Th i s script displays a greeting to the user based upon the current time. It is an example from JavaScript & jQuer y book */. ot just hit // before the statements.

## EXPRESSIONS
An expression evaluates into (results in) a single value. Broadly speaking
there are two types of expressions.
1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using the assignment operator (the equals sign). var color = 'beige'; The value of co 1 or is now beige. When you first declare a variable using the var keyword, it is given a special value of undefined. This will change when you assign a value to it. Technically, undefined is a data type like a number, string, or Boolean. 

2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
You can perform operations on any number of individual values (see next page) to determine a single value. For example: var area = 3 * 2; The value of area is now 6.Here the expression 3 * 2 evaluates into 6. This example also uses the assignment operator, so the result of the expression 3 * 2 is stored in the variable called area. Another example where an expression uses two values to yield a single value would be where two strings are joined to create a single string.

## OPERATORS
ARITHMETI C OPERATORS JavaScript contains the following mathematical operators, which you can use with numbers. You may remember some from math class. 
STRING OPERATOR There is just one string operator: the+ symbol. It is used to join the strings on either side of it. 

## FUNCTIONS
Functions let you group a series of statements together to perform a specific task. If different parts of a 
script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 

you can declear a function :  _function functionName(value){statments;}_
and call then it by: _functionName(value);_

**HOW DOES JAVASCRIPT MAKE WEB PAGES MORE INTERACTIVE! AND FUN!**
Javascript allow you to make web pages more interactive by accessing and modifying the content and markuo used in a web page while it is being viewed in the browser.
* ACCESS CONTENT You can use JavaScript to select any element, attribute, or text from an HTML page.
* MODIFY CONTENT You can use JavaScript to add elements, attributes, and text to the page, or remove them.
* PROGRAM RULES You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. 
* REACT TO EVENTS You can specify that a script should run when a specific event has occurred.

Javascript encompasses many of the traditional rules of programming.
it can make the web page feel interactive by responding to what the user does.


