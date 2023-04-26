# Day 09
# HTML 5

HTML5 (Hypertext Markup Language version 5) is the latest version of the markup language used to create and design web pages. It was released in 2014 and has since become the standard for web development. HTML5 includes many new features and improvements over its predecessor, HTML4, such as improved support for multimedia content, better semantics and structure, and enhanced accessibility for users with disabilities. HTML5 also supports new APIs that allow web developers to create more interactive and engaging websites, such as the Canvas API for 2D and 3D graphics and the Web Audio API for audio processing. Overall, HTML5 has made it easier for developers to create modern and responsive web applications that work across multiple platforms and devices.

1. Semantic Elements: HTML5 introduced new semantic elements that provide more meaning and context to the content of web pages, such as ```<header>, <footer>, <nav>, <article>, <section>, and <aside>```. These elements help search engines better understand the structure and content of web pages, and also make it easier for developers to create accessible and responsive websites.

```html
<header>
  <h1>My Website</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>
```

3. Canvas: HTML5 introduced the ```<canvas>``` element, which allows developers to create dynamic and interactive 2D and 3D graphics within a web page using JavaScript. This has enabled the creation of visually rich and engaging web applications.

```html
<canvas id="myCanvas" width="200" height="100"></canvas>
<script>
  var canvas = document.getElementById("myCanvas");
  var ctx = canvas.getContext("2d");
  ctx.fillStyle = "red";
  ctx.fillRect(0, 0, canvas.width, canvas.height);
</script>
```

These are just a few examples of the many features and improvements introduced by HTML5.

HTML Semantic Elements are HTML tags that provide meaning and context to web content. These elements help search engines and web browsers understand the structure and purpose of web pages, making it easier for them to crawl and index content accurately. Some examples of semantic HTML elements are ```<header>, <footer>, <nav>, <article>, <section>,``` and ```<aside>.```

Semantic HTML elements provide several benefits for web developers and users, including:

- Accessibility: Semantic HTML elements help improve accessibility by providing a more meaningful and structured way to describe content. This can make it easier for screen readers and other assistive technologies to understand the content of web pages.

- SEO: Semantic HTML elements can help improve search engine optimization (SEO) by providing more accurate information about the content of web pages. This can make it easier for search engines to understand and index content, which can lead to better search rankings.

- Maintenance: Semantic HTML elements can make it easier to maintain and update web pages by providing a more organized and structured way to organize content. This can make it easier to make changes and updates to web pages without affecting the overall structure and layout.

Here is an example of how semantic HTML elements can be used in a web page:

```html 
<!DOCTYPE html>
<html>
<head>
	<title>Example Page</title>
</head>
<body>
	<header>
		<h1>Example Page</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
	
	<section>
		<article>
			<header>
				<h2>Article 1</h2>
				<p>Posted on <time datetime="2023-04-24">April 24, 2023</time> by John Doe</p>
			</header>
			<p>This is the content of article 1.</p>
		</article>
		
		<article>
			<header>
				<h2>Article 2</h2>
				<p>Posted on <time datetime="2023-04-25">April 25, 2023</time> by Jane Doe</p>
			</header>
			<p>This is the content of article 2.</p>
		</article>
	</section>
	
	<footer>
		<p>Copyright © 2023 Example Page</p>
	</footer>
</body>
</html>
```

In this example, we have used semantic HTML elements such as ```<header>, <nav>, <section>, <article>, and <footer>``` to provide structure and meaning to the web page. This can make it easier for search engines to understand the content of the web page, which can improve search rankings.

Format Elements:

Format elements in HTML are used to format text and apply styles to web content. Some examples of format elements in HTML are ``<b>``,`` <i>``, ``<u>``, ``<strong>``, ``<em>``, ``<mark>``,`` <sub>``,`` <sup>``, and ``<strike>``.

Format elements provide several benefits for web developers and users, including:

- Readability: Format elements can make web content more readable by emphasizing important text and breaking up large blocks of text into smaller, more manageable chunks.

- Accessibility: Format elements can improve accessibility by providing a more structured and organized way to format web content. This can make it easier for users with disabilities to understand and navigate web pages.

- Aesthetics: Format elements can enhance the aesthetic appeal of web pages by adding style and visual interest to web content.

Here is an example of web page:

```html
<!DOCTYPE html>
<html>
<head>
	<title>Example Page</title>
	<style>
		h1 {
			font-size: 36px;
			font-weight: bold;
			color: #333;
			text-align: center;
			text-transform: uppercase;
			margin-bottom: 20px;
		}
		
		p {
			font-size: 18px;
			line-height: 1.5;
			color: #666;
			margin-bottom: 10px;
		}
		
		em {
			font-style: italic;
		}
		
		strong {
			font-weight: bold;
			color: #f00;
		}
		
		u {
			text-decoration: underline;
		}
	</style>
</head>
<body>
	<h1>Example Page</h1>
	
	<p>This is an <em>example</em> of how format elements can be used in HTML. You can use <strong>strong</strong> and <u>underline</u> tags to emphasize text, and <em>italic</em> tags to add emphasis or highlight key phrases. </p>
	
	<p>You can also use the <sup>superscript</sup> and <sub>subscript</sub> tags to format mathematical expressions or chemical formulas, or the <mark>mark</mark> tag to highlight important text. </p>
	
</body>
</html>
```

example of how format elements can be used in a web page:

```html
<!DOCTYPE html>
<html>
<head>
	<title>Example Page</title>
	<style>
		h1 {
			font-size: 36px;
			font-weight: bold;
			color: #333;
			text-align: center;
			text-transform: uppercase;
			margin-bottom: 20px;
		}
		
		p {
			font-size: 18px;
			line-height: 1.5;
			color: #666;
			margin-bottom: 10px;
		}
		
		em {
			font-style: italic;
		}
		
		strong {
			font-weight: bold;
			color: #f00;
		}
		
		u {
			text-decoration: underline;
		}
	</style>
</head>
<body>
	<h1>Example Page</h1>
	
	<p>This is an <em>example</em> of how format elements can be used in HTML. You can use <strong>strong</strong> and <u>underline</u> tags to emphasize text, and <em>italic</em> tags to add emphasis or highlight key phrases. </p>
	
	<p>You can also use the <sup>superscript</sup> and <sub>subscript</sub> tags to format mathematical expressions or chemical formulas, or the <mark>mark</mark> tag to highlight important text. </p>
	
</body>
</html>

```

In this example, we have used format elements such as ```<em>, <strong>, <u>, <sup>, <sub>, and <mark>``` to format and style the text in the web page. We have also used CSS to apply additional styles to the text, such as font size, color, and alignment. This can make the web page more visually appealing and easier to read.

How HTML helps in SEO:

HTML plays a crucial role in search engine optimization (SEO) by providing a structured and organized way to describe the content of web pages. Here are some of the ways that HTML can help improve SEO:

1. Title tags: HTML title tags provide a concise and accurate description of the content of web pages. Title tags appear in search engine results pages (SERPs) and are often the first thing that users see when they search for a particular keyword or phrase. Including relevant keywords in the title tag can help improve search rankings.

```html
<title>Example Page - Web Development</title>
```

2. Meta descriptions: HTML meta descriptions provide a brief summary of the content of web pages. Meta descriptions also appear in SERPs and can help attract users to click on a particular search result. Including relevant keywords and a call-to-action (CTA) in the meta description can improve click-through rates (CTR) and search rankings.

```html
<meta name="description" content="Learn about web development and how to build effective web applications.">
```

 
```

5. Semantic markup: HTML semantic elements (such as ```<header>, <nav>, <main>, <article>, <aside>, and <footer>```) provide a way to describe the structure and content of web pages in a more meaningful way. Using semantic markup can improve search rankings by making it easier for search engines to understand the content and purpose of different sections of the web page.
Example:

```html
<header>
	<h1>Example Page</h1>
	<nav>
		<ul>
			<li><a href="#introduction">Introduction</a></li>
			<li><a href="#title-tags">Title Tags</a></li>
			<li><a href="#images">Images</a></li>
		</ul>
	</nav>
</header>
<main>
	<article>
		<h2 id="introduction">Introduction</h2>
		<p>This is an example of how HTML can improve search engine optimization.</p>
	</article>
	<article>
		<h2 id="title-tags">Title Tags</h2>
		<p>HTML title tags provide a concise and accurate description of web pages.</p>
	</article>
	<article>
		<h2 id="images">Images</h2>
		<p>HTML image tags provide a way to describe images and other multimedia content on web pages.</p>
	</article>
</main>
<footer>
	<p>&copy; 2023 Example Company. All rights reserved.</p>
</footer>
```

In this example, we have used semantic markup to describe the structure and content of the web page. We have used ```<header>``` and ```<footer>``` to define the top and bottom sections of the web page, ```<nav>``` to define a navigation menu, ```<main>``` to define the main content of the web page, and ```<article>``` to define individual sections of the content. Using semantic markup can improve search rankings by making it easier for search engines to understand the purpose and meaning of different sections of the web page.


## HTML Video

In this tutorial, we will learn about videos in HTML with the help of examples.

The HTML ``<video>`` tag is used to embed a media player which supports video playback into the HTML page. We use the HTML ``<video>`` tag and the ``<source>`` tag to show the video. For example,

```html
<video width="320" height="190" controls>
    <source src="video.mp4" type="video/mp4">
</video>
```

In the above code,

- video.mp4 - path to the video we want to display
- video/mp4 - the type of resource we want to display
- controls - allows user to control the video
The video.mp4 file in the above example is located in the same directory as the HTML file.

### Attributes of HTML ```<video>``` tag
Let us look at the attributes supported by the HTML ```<video>``` tag.

- autoplay
- controls
- height and width
- loop
- muted
- src
- preload

We will learn about each of these in detail.

HTML Audio
In this tutorial, we will learn about the audio tag in HTML with the help of examples.

The HTML ```<audio>``` tag is used to embed a media player which supports audio playback into the HTML page. We use the HTML ```<audio>``` tag along with the ```<source>``` tag to add the audio player. For example,

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3">
</audio>
```

In the above code:

- audio.mp3 - path to the audio we want to display
- audio/mp3 - the type of resource we want to display.
The audio.mp3 file in the above example is located in the same directory as the HTML file.

Attributes of HTML <audio> tag
Let us look at the attributes supported by the HTML <audio> tag.

- autoplay
- controls
- loop
- muted
- src
- preload

# HTML Miscelleneous

## HTML Iframes
In this tutorial, we will learn about div iframes in HTML with the help of examples.

The HTML ```<iframe>``` tag is used to embed a webpage within a webpage. It is also called an inline frame. For example,

```html
<iframe src="https://programiz.pro" title="programiz pro website" height="500" width="500" ></iframe>
```


![iframe](../Images/iframe.png)

Here,

- src: It is used to specify the URL of the website to be loaded.
- title: It is good practice to include a title attribute so that screen readers can read the title to users.

## HTML Entities
In this tutorial, we will learn about entities in HTML with the help of examples.

The HTML entities are used to display reserved characters (characters that are used in HTML code), special characters, or invisible characters. For example,

```html
<p>This is a &lt;p&gt; tag.</p> 
```


Here, ```&lt; and &gt;``` are the HTML entities used to display ```<and>``` respectively.

If we were to use the ```<p>``` tag instead of ```&lt;p&gt;``` the browser would read it as a tag. Hence to display ```<p>``` we need to use ```&lt; and &gt;``` instead of ``<and> ``respectively.

## HTML Entities Syntax

HTML entities are represented by either their name or their number.

Entity names
We use &entity_name; to add reserved characters using Entity names. For example,
```&cent;```  would be displayed as ¢

## Entity number
We use &#entity_number; to add reserved characters using Entity number. For example, ```&#162;``` would also be displayed as ¢

All entity names and numbers start with an & and end with an ;.

Note: Not all entities have names, only characters that are commonly used have entity names.

## Special Characters
Special characters are characters that are not available on a general keyboard like ®, ©, ¢, etc.
We use HTML entities to add special characters to HTML documents. For example

```<footer> &copy;``` 2022 Programiz. All rights reserved. ```</footer>```
 

## Copyright Symbol Example
Invisible Characters
An invisible character is a character that is not visible when rendered in a document or text field. These characters can be used for various purposes, such as adding white space or formatting a document. For example,

```html
<p>Invi <span>&zwnj;</span>sible<span>&nbsp;</span>Cha<span>&zwnj;</span>racters</p>
```
 

Here, ```&zwnj;``` and ```&nbsp;``` are invisible characters. ```&zwnj;``` is a zero-width character whereas ```&nbsp;``` is a space character.

Some examples of invisible characters are – space, tab, zero-width space, etc.

 