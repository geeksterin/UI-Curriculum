# Links
Links are very important — they are what makes the web a web! To add a link, we need to use a simple element — ``<a>`` — "a" being the short form for "anchor". To make text within your paragraph into a link, follow these steps:

Choose some text. We chose the text "Mozilla Manifesto".
Wrap the text in an ``<a>`` element, as shown below:
```html
<a>Mozilla Manifesto</a>
```

Give the ``<a>`` element an href attribute, as shown below:
```html
<a href="">Mozilla Manifesto</a>
```

Fill in the value of this attribute with the web address that you want the link to:
```html
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
```

You might get unexpected results if you omit the https:// or http:// part, called the protocol, at the beginning of the web address. After making a link, click it to make sure it is sending you where you wanted it to.

# Audio, Video, Source tags
The <audio>, <video>, and <source> tags are used in HTML to embed audio and video content into a web page. Here is a brief explanation of what each tag does:

1. <audio> tag:
- The <audio> tag is used to embed audio content, such as music or speech, into a web page.
- It supports several attributes such as "src" to specify the URL of the audio file, "controls" to enable playback controls, and "autoplay" to start playback automatically when the page loads.
2. <video> tag:
- The <video> tag is used to embed video content, such as movies or TV shows, into a web page.
- It supports several attributes such as "src" to specify the URL of the video file, "controls" to enable playback controls, and "autoplay" to start playback automatically when the page loads.
3. <source> tag:
- The <source> tag is used in conjunction with the <audio> and <video> tags to provide multiple versions of the same media content in different formats or bitrates.
- This is useful for ensuring that the content can be played on different devices and connection speeds.
T- he <source> tag supports several attributes such as "src" to specify the URL of the media file, "type" to specify the MIME type of the file, and "media" to specify the media query to use when selecting the source.


In summary, the <audio>, <video>, and <source> tags provide a flexible and powerful way to embed audio and video content into a web page, and can be customized using a variety of attributes to provide the desired playback experience.

# List
In HTML, there are three types of lists: ordered lists, unordered lists, and descriptive lists. Here's a brief explanation of each type and their attributes:

Ordered Lists:
```html
<ol>
    <li>item-1</li>
    <li>item-2</li>
    <li>item-3</li>
</ol>
```
1. An ordered list is a list of items that are ordered numerically or alphabetically. It is created using the <ol> tag.
Each item in the list is represented by the <li> tag.
The attributes used in ordered lists include:
"start": specifies the starting number of the list.
"type": specifies the type of numbering used, such as decimal, uppercase letters, or lowercase Roman numerals.
"reversed": reverses the numbering of the list.

```html
<ul>
    <li>item-1</li>
    <li>item-2</li>
    <li>item-3</li>
</ul>
```
2. Unordered Lists:
An unordered list is a list of items that are not ordered in any particular way. It is created using the <ul> tag.
Each item in the list is represented by the <li> tag.
The attributes used in unordered lists include:
"type": specifies the type of bullet point used, such as circle, square, or disc.

```html
<dl>
    <dt>Title</dt>
    <dd>description</dd>
</dl>
```
3. Descriptive Lists:
A descriptive list is a list of items that are paired with their descriptions. It is created using the <dl> tag.
Each item in the list is represented by the <dt> tag, and the description is represented by the <dd> tag.
The attributes used in descriptive lists include:
None.