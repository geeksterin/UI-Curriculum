# Day 10

# What is CSS?
Like HTML, CSS is not a programming language. It's not a markup language either. CSS is a style sheet language. CSS is what you use to selectively style HTML elements. For example, this CSS selects paragraph text, setting the color to red:

```css
p {
  color: red;
}
```

# Syntax of CSS 

![Syntax](../Images/css-declaration-small.png)

The whole structure is called a ruleset. (The term ruleset is often referred to as just rule.) Note the names of the individual parts:

## Selector
This is the HTML element name at the start of the ruleset. It defines the element(s) to be styled (in this example, <p> elements). To style a different element, change the selector.

## Declaration
This is a single rule like color: red;. It specifies which of the element's properties you want to style.

## Properties
These are ways in which you can style an HTML element. (In this example, color is a property of the <p> elements.) In CSS, you choose which properties you want to affect in the rule.

## Property value
To the right of the property—after the colon—there is the property value. This chooses one out of many possible appearances for a given property. (For example, there are many color values in addition to red.)

Note the other important parts of the syntax:

1. Apart from the selector, each ruleset must be wrapped in curly braces. ({})
2. Within each declaration, you must use a colon (:) to separate the property from its value or values.
3. Within each ruleset, you must use a semicolon (;) to separate each declaration from the next one.
To modify multiple property values in one ruleset, write them separated by semicolons, like this:

```css
p {
  color: red;
  width: 500px;
  border: 1px solid black;
}
```

# Different types of selectors
There are many different types of selectors. The examples above use element selectors, which select all elements of a given type. But we can make more specific selections as well. Here are some of the more common types of selectors:

## Element selector 
Element selector: The element selector selects HTML elements based on the element name (or tag) for **example** p, h1, div, span, etc.

```css
h1 {
    color: red;
    font-size: 3rem;
}

p {
    color: white;
    background-color: gray;
}
```

## Id selector
The id selector uses the id attribute of an HTML element to select a specific element.

**Note:** An id of element is unique on a page to use id selector.

**Example:**
```css
#div-container{
    color: blue;
    background-color: gray;
}
```

## Class-selector
The class selector selects HTML elements with a specific class attribute.

To use class selector you must use ( . ) followed by class name in CSS. This rule will be applied to the HTML element with the class attribute “paragraph-class“

**Example**

```css
.paragraph-class {
    color:white;
    font-family: monospace;
    background-color: purple;
}
```

# Some Best practices to use css selectors

1. Use classes to select elements that are more specific, reusable and flexible than type selectors.
2. ID values can only be used once per page, so stick to using them for unique styles and global elements that are not repeated.


# Applying CSS to HTML
First, let's examine three methods of applying CSS to a document: with an external stylesheet, with an internal stylesheet, and with inline styles.

## External stylesheet
An external stylesheet contains CSS in a separate file with a .css extension. This is the most common and useful method of bringing CSS to a document. You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet.

You reference an external CSS stylesheet from an HTML ``<link>`` element:

```html
<!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <!-- bringing css -->
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>Hello Folks!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
```

## Internal stylesheet
An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a ``<style>`` element contained inside the HTML ``<head>``.

The HTML for an internal stylesheet might look like this:

```html
<!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <!-- internal css -->
    <style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }

      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>Hello Folks!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
```

### NOTE

1. In some circumstances, internal stylesheets can be useful. For example, perhaps you're working with a content management system where you are blocked from modifying external CSS files.

2. But for sites with more than one page, an internal stylesheet becomes a less efficient way of working. To apply uniform CSS styling to multiple pages using internal stylesheets, you must have an internal stylesheet in every web page that will use the styling. The efficiency penalty carries over to site maintenance too. With CSS in internal stylesheets, there is the risk that even one simple styling change may require edits to multiple web pages.

## Inline styles
Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute. The implementation of an inline style in an HTML document might look like this:

```html
<!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
  </head>
  <body>
    <h1 style="background-color: yellow;border: 1px solid black;">Hello Folks!</h1>
    <p style="color:red;">This is my first CSS example</p>
  </body>
</html>
```

### NOTE

1. Avoid using CSS in this way, when possible. It is the opposite of a best practice. First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

2. There are a few circumstances where inline styles are more common. You might have to resort to using inline styles if your working environment is very restrictive. For example, perhaps your CMS only allows you to edit the HTML body. You may also see a lot of inline styles in HTML email to achieve compatibility with as many email clients as possible.
