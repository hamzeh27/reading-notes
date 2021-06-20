# Html
***Hypertext Markup Language***
* the code that is used to structure a web page and its content.
* markup language that defines the structure of your content. 
* HTML consists of a series of elements like enclosing tags can make a word or image hyperlink to somewhere else.
* The main parts of our element are as follows:
1. The opening tag <p>
2. The closing tag </p>
3. The content
4. The element

### You can see the HTML code below

```
<html>
<head>
 <title>This is the Title of the Page</title>
</head>
<body>
 <h1>This is the Body of the Page</h1>
 <p>Anything within the body of a web page is
 displayed in the main browser window.</p>
</body>
</html>
```
# ***Creating a Web Page on a PC***
* Start
* #### All Programs (or Programs)
* #### Accessories
* #### Notepad
### Then type the code .
### Go to the File menu and select Save as. 
### Start your web browser. Go to the File menu and select Open. Browse to the file that you just created, select it and click on the Open button. 
# ***Creating a Web Page on a Mac***
* ### start up TextEdit. This should be in your Applications folder.
#### You might also like to download a free text editor for creating web pages called TextWrangler which is available from barebones.com
* ### Type the code
* ### Now go to the File menu and select Save as
####  You will probably see a window You want to select the Use .html button.
### DOCTYPES

Because there have beenseveral versions of HTML, eachweb page should 

begin with a DOCTYPE declaration to tell a browser which version of 

HTML the page is using (although browsers usually display the

page even if it is not included). 

HTML version | DOCTYPE
------------ | -------
HTML5        | ``` <!DOCTYPE html>```
HTML 4       | ```<!DOCTYPE html PUBLIC"-//W3C//DTD HTML 4.01 Transitional//EN""http://www.w3.org/TR/html4/loose.dtd">```
Transitional XHTML 1.0 | ```<!DOCTYPE html PUBLIC"-//W3C//DTD XHTML 1.0 Transitional//EN""http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"> ```
Strict XHTML 1.0 | ```<!DOCTYPE html PUBLIC"-//W3C//DTD XHTML 1.0 Strict//EN""http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">```
XML Declaration | ```<?xml version="1.0" ?>```

### Comment

If you want to add a comment to your code that will not be visible in the user's browser, you can add 

the text between these characters:
```
<!-- comment goes here -->
```

### ID attribute

Every HTML element can carry the id attribute. It is used to uniquely identify that element from other 

elements on the page. Its value should start with a letter or an underscore (not a number or any other 

character). It is important that no two

elements on the same page have the same value for their id attributes (otherwise the value is no 

longer unique).

# ~~Example:~~
#### you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites. To do this you can use the class attribute. 
### The class attribute on any element can share the same value. 
### <p class="important">For a one-year period from November 2010, the Marugame Genichiro-Inokuma Museum of Contemporary Art (MIMOCA) will host a cycle of four Hiroshi Sugimoto exhibitions.
### </p>
### <p>Each will showcase works by the artist thematically contextualized under the headings "Science," "Architecture," "History" and "Religion" so as to present a comprehensive panorama of the artist's oeuvre.
### </p>
### <p class="important admittance">Hours: 10:00 – 18:00 (No admittance after 17:30)
  
### IFrames
* a little window that has been cut into your page — and in that window you can see another page. 
* The term iframe is an abbreviation of inline frame.
* created using the <iframe> element.
* attributes that you will need
to know to use it:
### src
##### The src attribute specifies the URL of the page to show in the frame.
### height
##### The height attribute specifies the height of the iframe in pixels.
### width
##### The width attribute specifies the width of the iframe in pixels
# ~~Example:~~
#### <iframe
#### width="450"
#### height="350"
#### src="http://maps.google.co.uk/maps?q=moma+new+york &amp;output=embed">
 #### </iframe># </p>
  
 ### meta

###It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive. (If the page is time sensitive, it can  be set to expire.)
 
  ## HTML5 Layout

HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of 

these elements indicate the kind of content you will find in them. They are still subject to change, 

but that has not stopped many web page authors using them already.

* The ```<header>``` and ```<footer>``` elements can be used for:

  * The main header or footer that appears at the top or bottom of every page on the site.
  * A header or footer for anindividual ```<article>``` or ```<section>``` within the page.

* The ```<nav>``` element is used to contain the major navigational blocks on the site such as the primary 

site navigation.

* The ```<article>``` element acts as a container for any section of a page that could stand alone and 

potentially be syndicated. This could be an individual article or blog entry, a comment or forum post, 

or any other independent piece of content.

* The ```<aside>``` element has two purposes, depending on whether it is inside an ```<article>```

element or not.

When the ```<aside>``` element is used inside an <article> element, it should contain information that 

is related to the article but not essential to its overall meaning. For example, a pullquote or 

glossary 

might be considered as an aside to the article it relates to.

When the ```<aside>``` element is used outside of an ```<article>``` element, it acts as a container for content 

that is related to the entire page. For example, it might contain links to other sections of the site 

a list of recent posts, a search box, or recent tweets by the author.

* The ```<section>``` element groups related content together, and typically each section would have 

its own heading.

*  The ```<hgroup>``` element is to group together a set of one or more <h1> through <h6> elements so 

that they are treated as one single heading.

* ```<figure>```  It can be used to contain any content that is referenced from the main flow of an 

article (not just images).

* the ```<div>``` element will remain an important way to group together related elements, because you 

should not be using these new elements that you have just met for purposes other than those explicitly 

stated.
  
# ***PROCESS & Design***
* It's important to understand who your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
* Site maps allow you to plan the structure of a site.
* Wireframes allow you to organize the information that
will need to go on each page.
* Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
* You can differentiate between pieces of information
using size, color, and style. 
* You can use grouping and similarity to help simplify
the information you present.

# **JavaScript**
##  a lightweight, interpreted, or just-in-time compiled programming language with first-class functions 
* it's scripting language for Web pages.
* many non-browser environments also can use it.
* JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative
# What is a script ?
* A script is a series of instructions that the computer
can follow in order to achieve a goal.
* Each time the script runs, it might only use a subset of
all the instructions.
* Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
* To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help). 
# THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE
* Using the document object, you can access and change what content users see on the page and respond to how they interact with it. 
* the document object has:
### PROPERTIES
##### Properties describe characteristics of the current web page
### METHODS
##### Methods perform tasks associated with the document currently loaded in the browser
### EVENTS
##### You can respond to events, such as a user clicking or tapping on an element. 
# HOW A BROWSER SEES A WEB PAGE 
* RECEIVE A PAGE AS HTML CODE
* CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY
* USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN
# write script for web page 
* It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.
* The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file).
* If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created. 

