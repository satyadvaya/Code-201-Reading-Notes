# HTML & CSS
## Chapter1: _Structure_
HTML uses elements to describe the structure of pages and tags act like containers.
```
<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1></h1>
        <p></p>
        <h2></h2>
        <p></p>
    </body>
</html>
```
>Content between `<html>` tags is HTML code.<br>
Content between `<head>` tags contains information _about_ the page.<br>
Content between the `<title>` tags appears in the title bar or tabs at the top of the browser window.<br>
Content between `<body>` tags is shown inside the main browser window.<br>
Content between `<h1>` tags is the main heading.<br>
A paragraph of text appears between `<p>` tags.<br>
Content between `<h2>`, `<h3>`, _etc._ tags form a sub-heading.

`<p>`This is a paragraph.`</p>`<br>
An HTML element usually consists of a start tag and an end tag (each comprised of characters within brackets) along with the content inserted in between.

`<p lang="en-us">`Paragraph in English`</p>`<br>
Attributes appear on the opening tag of elements and require a lowercase name and a value in double quotes, separated by an equals sign.

## Chapter8: _Extra Markup_

DOCTYPES tell browsers which version of HTML you
are using.
- HTML4
- XHTML 1.0
    - Strict XHTML 1.0
    - Transitional XHTML 1.0
    - XHTML 1.0 Frameset
- HTML5

Comments can be added to code between the
`<!--` and `-->` markers which won't be visible within the user's browser .

`<p id="pullquote">`Paragraph text here.`</p>`<br>
The **id** attribute is used to uniquely identify that element from other elements on the page.<br>
`<p class="important admittance">`Paragraph text here.`</p>`<br>
The **class** attribute is used to identify several elements as being different from the other elements on the page, and class names are separated with a space when an element belongs to several classes.

The `<div>` and `<span>` elements allow you to group
block-level (`<h1>`, `<p>`, `<ul>`, & `<li>`) and inline (`<a>`, `<b>`, `<em>`, & `<img>`) elements together.

`<iframes>` cut windows into web pages through
which other pages can be displayed and use the `<src>`, `<height>`, `<width>`, `<scrolling>`, `<frameborder>`, and `<seamless>` attributes.

The `<meta>` element is contained within the `<head>` element and doesn't have a closing tag.  The most common attribute pairs are `<name>` and `<content>` (with name values of "descripton", "keywords", & "robots") and `<name>` and `<http-equiv>` (with http-equiv values of "author", "pragma", & "expires".<br>

Escape characters are used to display special characters reserved by HTML code, such as <, >, and ©.

## Chapter17: _HTML5 Layout_
The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.
- `<header>`
- `<footer>`
- `<nav>`
- `<article>`
- `<aside>`
- `<section>`
- `<hgroup>`
- `<figure>`
    - `<figcaption>`

The new elements provide clearer code and offer helpful alternatives to the `<div>` element).

Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.

To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed, which is available free from Google.

## Chapter18: _Process & Design_
It's important to understand who your target audience is, why they would visit your site, what they're attempting to achieve, what information they want to find, and how often they're likely to return.

Site maps allow you to plan the structure of a site.  Wireframes allow you to organize the information that will need to go on each page.

Design is about communication through the prioritization and organization of page content.  Visual hierarchy organizes perceptual contrast which helps visitors understand what you are trying to tell them.

Pieces of information can be differentiated by size, color, and style.

Grouping and similarity help simplify how information is presented and make a design easier to comprehend.
- Proximity
- Closure
- Continuance
- White Space
- Color
- Borders

# JavaScript & jQuery
## Chapter1: _The ABC of Programming_
### What is a Script and How Do I Create One?
A script is a series of instructions that the computer can follow in order to achieve a goal.

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
- Define the goal
- Design the script
    - Flowchart
- Code each step

### How Do Computers Fit in with the World around Them?
Computers create models of the world using data.

The models use objects to represent physical things.  Objects can have:
- Properties that tell us about the object;
- Methods that perform tasks using the properties of that object;
- Events which are triggered when a user interacts with the computer.

Computers use data to create models of things in the real world.  The events, methods, and properties of an object all relate to each other.  Events can trigger methods, and methods can retrieve or update an object's properties.

Web browsers use HTML markup to create a model of the web page.  Each element creates its own node (which is a kind of object).

To make web pages interactive, you write code that uses the browser's model of the web page.

### How Do I Write a Script for a Web Page?
It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension.<br>

`<script src="XXX.js"></script>`<br>
The HTML `<script>` element is used in HTML pages
to tell the browser to load the JavaScript file (rather like the `<link>` element can be used to load a CSS file with the `<link rel="stylesheet" href="XXX.css" />` reference at the bottom of the `<head>` element).  Most scripts are added at the bottom of the `<body>` element within the HTML file.<br>

If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.