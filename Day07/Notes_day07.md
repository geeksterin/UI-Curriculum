# Day 02


# Block and Inline HTML

In HTML, elements are classified as either block-level or inline elements based on their behavior and how they are displayed on the web page.

Block-level elements are displayed as a block on the page, taking up the full width available to them and creating a new line after the element. They are typically used for larger pieces of content, such as headings, paragraphs, and lists.

Example of block-level element:

```html
<div>
  <h1>Heading 1</h1>
  <p>This is a paragraph of text.</p>
  <ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
  </ul>
</div>
```

In this example, the ```<div>``` element is a block-level element, and it contains other block-level elements such as ```<h1>, <p>, and <ul>.``` When the page is rendered, each of these elements will be displayed as a block, taking up the full width of the container element, and creating a new line after each one.

Inline elements, on the other hand, are displayed inline with the surrounding content, without creating a new line after the element. They are typically used for smaller pieces of content, such as links, images, and text formatting.

Example of inline element:

```html
<p>This is a paragraph with a <strong>strong</strong> and <em>emphasized</em> text.</p>
```

In this example, the ```<strong> and <em>``` elements are inline elements, and they are used to add emphasis to certain words within the paragraph. When the page is rendered, these elements will be displayed inline with the surrounding text, without creating a new line.

It's important to note that some elements, such as ```<span> and <a>```, can be either block-level or inline, depending on how they are used and whether they are given a specific width or height.

## Synatx

Give the ``<a>`` element an href attribute, as shown below:
```html
<a href="">Mozilla Manifesto</a>
```

Fill in the value of this attribute with the web address that you want the link to:
```html
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
```


You might get unexpected results if you omit the https:// or http:// part, called the protocol, at the beginning of the web address. After making a link, click it to make sure it is sending you where you wanted it to.

## Types of Navigation
1. Inter Navigation-The above exapmple discussed was related to Inter navigation. So we can use clickable elements that allow users to navigate to other pages or resources on the web. To create a hyperlink in HTML, you use the ``<a>`` tag and set the href attribute to the URL of the page you want to link to.



```html
<a href="https://www.geekster.in/">About</a>
```



2. Intra Navigation - An anchor is a point within a web page that can be targeted by a link. To create an anchor, you can use the id attribute on any HTML element. For example, to create an anchor at the beginning of a section, you could use:

```html
<section id="my-section">
  <!-- content of section here -->
</section>
```
To link to this anchor from another part of the same page, you can use an anchor link. An anchor link is simply a regular link with the href attribute set to the # symbol followed by the id of the anchor. For example:

```html
<a href="#my-section">Go to my section</a>
```
When the user clicks on this link, the browser will scroll to the section with the id "my-section".


# Images 
The ``<img>`` tag in HTML is used to insert images into a web page. It is a self-closing tag, which means that it does not require a closing tag.

The ``<img>`` tag has a required src attribute, which specifies the URL of the image to be displayed. For example:

```html
<img src="path/to/image.jpg" alt="A description of the image">
```

The alt attribute is also required and should provide a text description of the image for users who cannot see it or have images turned off in their browser. It is also used by screen readers for accessibility purposes.

In addition to the src and alt attributes, there are several optional attributes that can be used with the ``<img>`` tag, including:

- width and height: These attributes specify the width and height of the image in pixels.

- title: This attribute provides additional information about the image that is displayed when the user hovers over it.

- loading: This attribute tells the browser how to load the image, with possible values of "lazy" or "eager". "Lazy" means the image will be loaded only when


## HTML Bold 

In this tutorial, we will learn about implementing bold text in HTML with the help of examples.

We use the HTML ```<b>`` tag or the HTML ```<strong>``` tag to make text bold. For example,

# Assignment
- https://priyanshu-240499.github.io/Assignments-CSS/html_day2/day2.html