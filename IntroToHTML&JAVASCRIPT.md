# Introduction to HTMLE & JAVASCRIPT

As we mentioned earlier WEB pages constructs by using HTML, CSS and JS all togather, 
also we said that HTML stands for hyperText Markup Language that used to describes and defines the content and basic structure of the websites.

JS control the behavior of websites. It's degined to manipulate web pages and it is used to create interactive functionality.

<img align="right" width="200" height="200" src="https://www.visualcapitalist.com/wp-content/uploads/2019/08/top-100-websites-prev-1000x600.jpg">


## BUT How People Access the Web?

People access websites using software called a web browser. Popular examples include Firefox, Internet Explorer, Chrome, and Opera. When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website. Web servers are special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them. People are accessing websites on an increasing range of devices including desktop computers, laptops, tablets, and mobile phones. It is important to remember that various devices have different screen sizes and some have faster connections to the web than others.

<img align="right" width="200" height="200" src="https://www.ionos.com/digitalguide/fileadmin/DigitalGuide/Teaser/datensicherung-von-verschiedene-devices-c.jpg">



## BUILDING THE STRUCTURE OF THE PAGE

<img align="right" width="200" height="200" src="https://codebrainer.azureedge.net/images/what-is-html.jpg">

Will HTML Uses Elements to Describe the Structure of Pages. Each element has an opening tag and a closing Tags act like containers. They tell you something about the information that lies between their opening and closing tags

tags
* The opening <html> tag indicates that anything between it and a closing </html> tag is HTML code.
* The <body> tag indicates that anything between it and the closing </body> tag should be shown inside the main browser window.
* Words between <h1> and </h1> are a main heading.
* A paragraph of text appears between these <p> and </p> tags.
* Words between <h2> and </h2> form a sub-heading.
* Here is another paragraph between opening <p> and closing </p> tags.
* Another sub-heading inside <h2> and </h2> tags.
* Another paragraph inside <p> and </p> tags.
* The closing </body> tag indicates the end of what should appear in the main browser window.
* The closing </html> tag indicates that it is the end of the HTML code.

## HISTORY OF _HTML_

Since the web was first created, there have been several different versions of HTML. Each new version was designed to be an improvement on the last.

* HTML 4 Released 1997, HTML 4 had some presentational elements to control the appearance of pages, authors are not recommended to use them any more.
* XHTML 1.0 Released 2000, In 1998, a language called XML was published. Its purpose was to allow people to write new markup languages. Since HTML was the most widely used markup language around.
* HTML5 Released 2000, In HTML5, web page authors do not need to close all tags, and new elements and attributes will be introduced.

And that is why you type each time DOCTYPE in the beginning of the HTML code to tell a browser which version of HTML the page is using. 

After definding all of that 


## TRADITIONAL HTML LAYOUTS


For a long time, web page authors used <div> elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar). Authors used class or id attributes to indicate the role of the <div> element in the structure of the page.

* Headers & Footers <header> <footer>, The main header or footer that appears at the top or bottom of every page on the site.
* Navigation <nav>, The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.
* Articles <article>, The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.
* Asides <asides>. The <aside> element has two purposes, depending on whether it is inside an <article> element or not.
* Sections <section>. The <section> element groups related content together, and typically each section would have its own heading.

## WHO IS THE SITE FOR?


Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

**ASK YOURSELF**

* What is the age range of your target audience?
* Will your site appeal to more women or men? What is the mix?
* Which country do your visitors live in?
* Do they live in urban or rural areas?
* What is the average income of visitors?
* What level of education do they have?
* What is their marital or family status?
* What is their occupation?
* How many hours do they work per week?
* How often do they use the web?
* What kind of device do they use to access the web?

Now that you know who your visitors are, you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason. And what is the type of information they need. How often they will visit it. 

# JAVASCRIPT

<img align="right" width="200" height="200" src="https://e3arabi.com/wp-content/uploads/2020/07/technology-1283624_1920.jpg">


**HOW JAVASCRIPT MAKES WEB PAGES MORE INTERACTIVE! AND FUN!**
Javascript allow you to make web pages more interactive by accessing and modifying the content and markuo used in a web page while it is being viewed in the browser.
* ACCESS CONTENT You can use JavaScript to select any element, attribute, or text from an HTML page.
* MODIFY CONTENT You can use JavaScript to add elements, attributes, and text to the page, or remove them.
* PROGRAM RULES You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. 
* REACT TO EVENTS You can specify that a script should run when a specific event has occurred.

Javascript encompasses many of the traditional rules of programming.
it can make the web page feel interactive by responding to what the user does.

## WHAT IS A SCRIPT AND HOW DO I CREATE ONE!!

A script is a series of instructions that a computer can follow to achieve a goal. 

Script are made up of interactions a computer can follow step-by-step.
Acbrowser may use different parts of the script depending on how the user interacts with the web page.
Scripts can run different sections of the code in response to the situation around them.

**To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.**

Humans can achieve complex goals without thinking about them too much, for example you might be able to drive a car, cook breakfast, or send an email without a set of detailed instructions. But the first time we do these things they can seem daunting. Therefore, when learning a new skill, we often break it down into smaller tasks, and learn one of these at a time. With experience these individual tasks grow familiar and seem simpler. Some of the scripts you will be reading or writing when you have finished this book will be quite complicated and might look intimidating at first. However, a script is just a series of short instructions, each of which is performed in order to solve the problem in hand. This is why creating a script is like writing a recipe or manual that allows a computer to solve a puzzle one step at a time. It is worth noting, however, that a computer doesn't learn how to perform tasks like you or I might; it needs to follow instructions every time it performs the task. So a program must give the computer enough detail to perform the task as if every time were its first time. 

**Start with the big picture of what you want to achieve, and break that down into smaller steps.**
1. DEFINE THE GOAL First: you need to define the task you want to achieve. You can think of this as a puzzle for the computer to solve.
2. DESIGN THE SCRIPT: To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart. You can then write down individual steps that the computer needs to perform in order to complete each individual task (and any information it needs to perform the task), rather like writing a recipe that it can follow.
3. CODE EACH STEP :Each of the steps needs to be written in a programming language that the compu ter understands. In our case, this is JavaScript. As tempting as it can be to start coding straight away, it pays to spend time designing your script before you start writing it. 

**FROM STEPS TO CODE**
Every step for every task shown in a flowchart needs to be written in a language the computer can understand and follow. In this book, we are focussing on the JavaScript language and how it is used in web browsers. Just like learning any new language, you need to get to grips with the:
* Vocabulary: The words that computers understand
* Syntax: How you put those words together to create instructions computers can follow Along with learning the language itself, if you are new to programming, you will also need to learn how a computer achieves different types of goals using a programmatic approach to problem-solving.

You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them. Computers solve problems programmatically; they follow series of instructions, one after another. The type of instructions they need are often different to the type of instructions you might give to another human. Therefore, throughout the book you will not only learn the vocabulary and syntax that JavaScript uses, but you will also learn how to write instructions that computers can follow. For example, when you look at the picture on the left how do you tell which person is the tallest?
A computer would need explicit, step-by-step
instructi0ns, such as:
1. Find the height of the first person
2. Assume he or she is the "tallest person"
3. Look at the height of the remaining people oneby-one and compare their height to the "tallest person" you have found so far
4. At each step, if you find someone whose height is greater than the current "tallest person", he or she becomes the new "tallest person"
5. Once you have checked all the people, tell me which one is the tallest So the computer needs to look at each person in turn, and for each one it performs a test ("Are they taller than the current tallest person?"). Once it has done this for each person it can give its answer. 


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

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements. 

<img align="right" width="200" height="200" src="https://fireship.io/courses/javascript/img/function-declaration.png">

you can declear a function :  _function functionName(value){statments;}_
and call then it by: _functionName(value);_


[THE END](https://c4.wallpaperflare.com/wallpaper/76/1011/652/blue-text-fog-blue-wallpaper-preview.jpg)



