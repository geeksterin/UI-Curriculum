- [What is the Internet?](#what-is-the-internet)
- [What is the Web?](#what-is-the-web)
- [Web Terminology](#web-terminology)
- [Browser Features](#browser-features)
    - [Page Inspector](#page-inspector)
    - [Web Console](#web-console)
    - [JavaScript Debugger](#javascript-debugger)
    - [Network Monitor](#network-monitor)
    - [Responsive Design Mode](#responsive-design-mode)
- [What is HTML](#what-is-html)
- [Anatomy of an HTML Element](#anatomy-of-an-html-element)
    - [Nesting Elements](#nesting-elements)
    - [Empty Elements](#empty-elements)
    - [Attributes](#attributes)
- [Anatomy of an HTML Document](#anatomy-of-an-html-document)
- [Marking up text](#marking-up-text)
    - [Heading](#headings)
    - [Paragraphs](#paragraphs)
    - [Lists](#lists)
    - [Links](#links)
- [Project](#project)


# What is the Internet?
The internet is simply a network of computers that communicate with each other to send and receive data (information).

Each of these computers on the internet can be distinguished and located by a unique number called an IP Address. An IP Address looks something like this: 168.212.226.204

# What is the Web?
The Web is a subset of the internet.

Like every other computer network out there, the Web is made up of two main components: the web browser client and the web server.

The client requests the data and the server shares or serves its data. To achieve this, the two parties have to establish an agreement. That agreement is called the Application Programming Interface or in short, the API.

But this data has to be arranged and formatted into a form that's understandable by end-users who have a wide range of technical experiences and abilities.

This is where HTML, CSS, JavaScript and the whole concept of web development come into play.

# Web Terminology
1. HTML (HyperText Markup Language) - the "programming" language used to write web pages
2. Source file - the set of tags and text which make up a web page. Browsers process the source file to make the web page look the way the designer wanted it to look.
3. URL (Uniform Resource Locator) - a web address; indicates the location of a web resource as well as the protocol needed to access it
4. Protocol - ground rules or "language" that internet computers use to "talk" with each other
5. HTTP (HyperText Transfer Protocol) - the internet protocol which allows web pages to work
6. FTP (File Transfer Protocol) - allows computers to exchange files over a network
7. Web page - a single page on the web (a "homepage" is the first web page on a web site)
8. Web site - a collection of web pages, usually on a particular topic or business
9. Web browser/navigator/client - the software application which displays web pages
10. Web server - the computer or network of computers which stores web pages

# Browser Features

## Page Inspector
![Page Inspector](./Images/landingpage_pageinspector.png)

View and edit page content and layout. Visualize many aspects of the page including the box model, animations, and grid layouts

## Web Console
![Web Console](./Images/landingpage_console.png)

See messages logged by a web page and interact with the page using JavaScript.

## JavaScript Debugger
![JavaScript Debugger](./Images/landingpage_debugger.png)

Stop, step through, and examine the JavaScript running on a page.

## Network Monitor
![Network Monitor](./Images/landingpage_network.png)

See the network requests made when a page is loaded.

## Responsive Design Mode
![Responsive Design Mode](./Images/landingpage_responsivedesign.png)

See how your website or app will look and behave on different devices and network types.

# What are three application layers
- Three-tier architecture is a software application architecture that organizes applications into three logical and physical computing tiers.
The three tiers are:
 1. Presentation tier: user interface
 2. Application tier: where data is processed
 3. Data tier: where the data associated with the application is stored and managed.
- Three-tier architecture has a chief benefit:
1. Each tier runs on its own infrastructure, which allows each tier to be developed simultaneously by separate development teams.
2. Each tier can be updated or scaled as needed without impacting the other tiers.

# What is front end development 
It is the presentation tear or the user interface of an application. Everything you see on a website, like buttons, links, animations, and more, were created by a front end web developer. It is the front end developer's job to take the vision and design concept from the client and implement it through code.

# What is HTML

- HTML (Hypertext Markup Language) is a standard markup language used to create web pages. It was created by Tim Berners-Lee in the late 1980s to help share scientific information between researchers. Here is a brief history of HTML:

- HTML was first standardized in 1993 as HTML 2.0.
- HTML 3.0 was released in 1995 and introduced new features such as tables and backgrounds.
- HTML 4.0 was released in 1997 and added support for Cascading Style Sheets (CSS) and scripting languages like JavaScript.
- XHTML (Extensible HTML) was introduced in 2000 as the successor to HTML, but it never gained widespread adoption.
- HTML5 was first introduced in 2008 and became a W3C recommendation in 2014. It added new semantic tags, multimedia support, and improved accessibility features.
- The latest version, HTML5.3, was published in 2018 and includes new features such as the "picture" element for responsive images and support for the Web Speech API.
- HTML continues to evolve as new features and technologies are developed for the web.

# Anatomy of an HTML element

![Anatomy](./Images/grumpy-cat-small.png)

The main parts of our element are as follows:

1. The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.

2. The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

3. The content: This is the content of the element, which in this case, is just text.

4. The element: The opening tag, the closing tag, and the content together comprise the element.

## Empty elements
Some elements have no content and are called empty elements. Take the ```<img>``` element that we already have in our HTML page:

# Structure of html(head tag vs body tag, also what is doctype/is it a tag?)

```html
<html>
    <head></head>
    <body></body>
</html>
```
The head and body tags are two of the most important tags in HTML, and they serve different purposes. Here is a brief explanation of what each tag does:

Head Tag:

- The <head> tag is used to define the head section of an HTML document, which contains information about the document itself.
- This section typically includes metadata such as the document title, keywords, author information, and character encoding information.
- Other common elements found in the head section include links to external stylesheets, scripts, and other resources used by the page.
Body Tag:

- The <body> tag is used to define the main content area of an HTML document, which is visible to the user in the web browser.
- This section typically includes the text, images, videos, and other media that make up the actual content of the page.
- Other common elements found in the body section include headings, paragraphs, lists, links, images, forms, and tables.

In summary, the <head> tag is used to define the metadata and resources used by the page, while the <body> tag is used to define the main content area visible to the user.

#  HTML-4 vs HTML-5 
HTML5 is the latest version of HTML (Hypertext Markup Language) and has several advantages over HTML4. Here are some of the key differences between HTML4 and HTML5:

Semantic tags: HTML5 includes many new semantic tags such as header, footer, section, article, nav, and aside, which make it easier for search engines and screen readers to understand the structure of the page.

Multimedia support: HTML5 includes native support for audio and video, which means that you can embed multimedia content directly into your HTML code without the need for additional plugins like Flash.

Improved form elements: HTML5 introduces new form elements such as date pickers, color pickers, and range sliders, which make it easier to create user-friendly forms.

Canvas and SVG support: HTML5 introduces support for the canvas and SVG elements, which allow for the creation of interactive graphics and animations without the need for additional plugins.

Offline support: HTML5 introduces new features such as the Application Cache and Local Storage, which allow web applications to work offline and store data locally on the user's device.

Better error handling: HTML5 has better error handling and recovery mechanisms, which means that web pages are more likely to render correctly even if there are errors in the code.


# Nesting elements
You can put elements inside other elements too — this is called nesting. If we wanted to state that our cat is very grumpy, we could wrap the word "very" in a ```<strong>``` element, which means that the word is to be strongly emphasized:

```html
<p>My cat is <strong>very</strong> grumpy.</p>
```

You do however need to make sure that your elements are properly nested. In the example above, we opened the ```<p>``` element first, then the ```<strong>``` element; therefore, we have to close the ```<strong>``` element first, then the ```<p> ```element. The following is incorrect:

```html
<p>My cat is <strong>very grumpy.</p></strong>
```

The elements have to open and close correctly so that they are clearly inside or outside one another. If they overlap as shown above, then your web browser will try to make the best guess at what you were trying to say, which can lead to unexpected results. So don't do it!

```html
<img src="images/firefox-icon.png" alt="My test image">
```
This contains two attributes, but there is no closing ```</img>``` tag and no inner content. This is because an image element doesn't wrap content to affect it. Its purpose is to embed an image in the HTML page in the place it appears.

**Note:** The src,alt in img tag are known as attributes. so let's see what attributes are:

## Attributes

![Attributes](./Images/grumpy-cat-attribute-small.png)

Attributes contain extra information about the element that you don't want to appear in the actual content. Here, class is the attribute name and editor-note is the attribute value. The class attribute allows you to give the element a non-unique identifier that can be used to target it (and any other elements with the same class value) with style information and other things.

An attribute should always have the following:

1. A space between it and the element name (or the previous attribute, if the element already has one or more attributes).

2. The attribute name followed by an equal sign.
3. The attribute value wrapped by opening and closing quotation marks.

# Project+Revisit👇

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>My test page</title>
  </head>
  <body>
    <h1>This is a first level heading in HTML.</h1>
  <h2>This is a second level heading in HTML.</h2>
  <h3>This is a third level heading in HTML.</h3>
  <p>This is a <em>paragragh</em> As you can see, I placed an empahisis on the word "paragraph".</p>
  <p>The main essence of this tutorial is to:</p>
    <ul>
       <li>Show you how to format a web document with HTML</li>
       <li>Show you how to design a web page with CSS</li>
       <li>Show you how to program a web document with JavaScript</li>
    </ul>
  </body>
</html>
```

![index](./Images/index.png)

**Here We have the following:**

1. ```<!DOCTYPE html>``` — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.

2. ```<html></html>``` — the ```<html>``` element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.

3. ```<head></head>``` — the ```<head>``` element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.

4. ```<meta charset="utf-8">``` — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
5. ```<meta name="viewport" content="width=device-width">``` — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.
6. ```<title></title>``` — the ```<title>``` element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
7. ``<body></body>`` — the ``<body>`` element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

# Marking up text
This section will cover some of the essential HTML elements you'll use for marking up the text.

## Headings
Heading elements allow you to specify that certain parts of your content are headings — or subheadings. In the same way that a book has the main title, chapter titles, and subtitles, an HTML document can too. HTML contains 6 heading levels, ``<h1>`` - ``<h6>``, although you'll commonly only use 3 to 4 at most:

```html
<!-- 4 heading levels: -->
<h1>My main title</h1>
<h2>My top level heading</h2>
<h3>My subheading</h3>
<h4>My sub-subheading</h4>
```
```
Note: Anything in HTML between <!-- and --> is an HTML comment. The browser ignores comments as it renders the code. In other words, they are not visible on the page - just in the code. HTML comments are a way for you to write helpful notes about your code or logic.
```

Now try adding a suitable title to your HTML page just above your ``<img>`` element.

```
Note: You'll see that your heading level 1 has an implicit style. Don't use heading elements to make text bigger or bold, because they are used for accessibility and other reasons such as SEO. Try to create a meaningful sequence of headings on your pages, without skipping levels.
```

## Paragraphs
As explained above, <p> elements are for containing paragraphs of text; you'll use these frequently when marking up regular text content:

```html
<p>This is a single paragraph</p>
Add your sample text (you should have it from What will your website look like?) into one or a few paragraphs, placed directly below your <img> element.
```

# Project
Now lets make a resume with the help of html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bittoo Aggarwal</title>
</head>
<body>
    <h1>Bittoo Aggarwal</h1>
    <p>Software Developer, Educator at Geekster</p>
    <a href="https://www.linkedin.com/in/bittoo-aggarwal/">Linkedin</a>
    <a href="https://github.com/bitz1119">Github</a>
    <hr>
    <h2>Experience</h2>
    <h3> Software developer at Amazon</h3>
    <p>I work with amazon in transportation team, some more description Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, ullam! Maxime officiis consequuntur libero eaque reprehenderit quisquam nam ab vitae totam id commodi laborum enim, sint ea odit quasi soluta!
        <br>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Provident iusto ut praesentium modi. Incidunt atque voluptatem, dignissimos officiis reprehenderit est!
    </p>
    <hr>

    <h3> Educator at Geekster</h3>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempora cum inventore aliquam, nulla eos dignissimos ipsum voluptas id, dolores suscipit totam nostrum perferendis alias, expedita quaerat distinctio asperiores! Nobis, aliquid.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere ipsa ab qui autem nesciunt vel consequatur non totam, temporibus excepturi voluptatem iure impedit ut repellendus earum necessitatibus nemo eligendi, animi debitis reiciendis suscipit. Unde iure obcaecati dolores, numquam quibusdam rerum facilis a quam quos ad ullam consectetur reiciendis deserunt similique.
    </p>
    <hr>

    <h2>Skills</h2>
    <!-- how to comment -->
    <!-- I want to add skills list -->
    <ul>
        <li>Java</li>
        <li>JavaScript</li>
        <li>Testing</li>
        <li>API Designing</li>
        <li>System Design</li>
    </ul>

    <hr>
    <h2>Hobbies</h2>
    <ol>
        <li>Table Tennis</li>
        <li>Reading Books</li>
        <li>Biography</li>
        <li>Teaching</li>
    </ol>
    <hr>
</body>
</html>
```

Above Resume will look like this on browser,

![resume](./Images/resume.png)
![resume2](./Images/resume2.png)
