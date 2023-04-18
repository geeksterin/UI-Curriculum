# Day 11

# CSS Colors

## rgb() function in CSS
RGB is a combination of three colors (Red, Green and Blue) that is used in all computer systems for colored display. As we know, these are the basic colors and by combining them we can obtain any color which is visible in the color spectrum.

In CSS, these colors are defined in the form of a function rgb(): (red, green, blue). The range of all these colors is defined from 0 to 255 defines the intensity of a color, and we can change the colors by changing these values. The intensity of these colors is well defined in the given example.

**Example**

```css
rgb (0, 255, 0)
```
This combination returns the green color because it has the highest intensity and the other two colors have 0 intensity.

By changing the intensities of all three colors we get the different colors such as

```
rgb(255, 255, 255) displays the white color
and rgb(0, 0, 0) gives the black color.
```

## RGBA Colors
In CSS RGBA is also a format to display colors with the extension of Alpha. The structure of this color function is given below.

rgba(Red, Green, Blue, Alpha)
In this function, an Alpha is used to express the opacity of a color. In CSS opacity property is used to set the transparency of a color and its range lies between 0.0 to 1.0, where 0.0 represents the fully transparent and 1.0 represents the fully opaque. You will better understand from the given example.

```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>
<h1 style="background-color:rgba(0,255,0,0.0);">Green</h1>
<h1 style="background-color:rgba(0,255,0,0.25);">Green</h1>
<h1 style="background-color:rgba(0,255,0,0.5);">Green</h1>
<h1 style="background-color:rgba(0,255,0,0.75)">Green</h1>
<h1 style="background-color:rgba(0,255,0,1.0)">Green</h1>
</body>
</html>
```

![color](./Images/Color-in-CSS-2.png)

In the above given example, we set the value of alpha from 0.0 (fully transparent) to 1.0 (fully opaque) and you can see the difference in intensity of transparency.

## CSS HEX Colors
In CSS colors can also be specified with hexadecimal values, it is just another way to represent colors. In CSS, it is the most common way to specify a color by using hexadecimal values with an “#” sign such as #RRGGBB. Whereas, R, G, B are the codes for red, green and blue, respectively.

Hexadecimal numbers with the combination of 0-9 and A-F are used to represent a color in CSS. Some examples of basic HEX colors are given below:

```
#ffffff: it represents the white color and
#000000: it represents the black color.
```

# Few CSS properties

## color
The color CSS property sets the foreground color value of an element's text and text decorations, and sets the currentcolor value. currentcolor may be used as an indirect value on other properties and is the default for other color properties, such as border-color.

## Syntax

```css
/* Keyword values */
color: currentcolor;

/* <named-color> values */
color: red;
color: orange;
color: tan;
color: rebeccapurple;

/* <hex-color> values */
color: #090;
color: #009900;
color: #090a;
color: #009900aa;

/* <rgb()> values */
color: rgb(34, 12, 64, 0.6);
color: rgb(34.0 12 64 / 60%);
```

The color property is specified as a single ``<color>`` value.

Note that the value must be a uniform color. It can't be a ``<gradient>``, which is actually a type of ``<image>``.

Values
``<color>``
Sets the color of the textual and decorative parts of the element.

## background-color
The background-color CSS property sets the background color of an element.

## Syntax

```css
/* Keyword values */
background-color: red;
background-color: indigo;

/* Hexadecimal value */
background-color: #bbff00;    /* Fully opaque */
background-color: #bf0;       /* Fully opaque shorthand */
background-color: #11ffee00;  /* Fully transparent */
background-color: #1fe0;      /* Fully transparent shorthand  */
background-color: #11ffeeff;  /* Fully opaque */
background-color: #1fef;      /* Fully opaque shorthand  */

/* RGB value */
background-color: rgb(255, 255, 128);        /* Fully opaque */
background-color: rgba(117, 190, 218, 0.5);  /* 50% transparent */
```