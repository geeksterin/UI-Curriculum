# Position

The position CSS property sets how an element is positioned in a document. The top, right, bottom, and left properties determine the final location of positioned elements.

# Syntax

```css
position: static;
position: relative;
position: absolute;
position: fixed;
position: sticky;
```

# Values

## static

The element is positioned according to the normal flow of the document. The `top`,` right`, `bottom`, `left`, and `z-index` properties have no effect. This is the default value.

## relative

The element is positioned according to the normal flow of the document, and then offset relative to itself based on the values of `top`, `right`, `bottom`, and `left`. The offset does not affect the position of any other elements; thus, the space given for the element in the page layout is the same as if position were static.
This value creates a new stacking context when the value of z-index is not auto. Its effect on `table-*-group`,` table-row`,` table-column`,` table-cell`, and `table-caption` elements is undefined.

## absolute

The element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to its closest positioned ancestor, if any; otherwise, it is placed relative to the initial containing block. Its final position is determined by the values of `top`, `right`, `bottom`, and `left`.
This value creates a new stacking context when the value of `z-index` is not auto. The margins of absolutely positioned boxes do not collapse with other margins.

## fixed

The element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to the initial containing block established by the viewport, except when one of its ancestors has a `transform`, `perspective`, or `filter` property set to something other than `none` (see the CSS Transforms Spec), or the will-change property is set to `transform`, in which case that ancestor behaves as the containing block. (Note that there are browser inconsistencies with `perspective` and `filter` contributing to containing block formation.) Its final position is determined by the values of `top`, `right`, `bottom`, and `left`.
This value always creates a new stacking context. In printed documents, the element is placed in the same position on every page.

## sticky

The element is positioned according to the normal flow of the document, and then offset relative to its nearest scrolling ancestor and containing block (nearest block-level ancestor), including table-related elements, based on the values of `top`, `right`, `bottom`, and `left`. The offset does not affect the position of any other elements.
This value always creates a new stacking context. Note that a sticky element "sticks" to its nearest ancestor that has a "scrolling mechanism" (created when `overflow` is `hidden`, `scroll`, `auto`, or `overlay`), even if that ancestor isn't the nearest actually scrolling ancestor.

# Z-index

Z-index is a CSS property that determines the stacking order of HTML elements on a web page. The higher the z-index value of an element, the more likely it is to be placed on top of other elements.

Here are some important notes on z-index:

1. The default value of z-index is 0.

2. The z-index property can be applied to any positioned element (i.e., an element with position: relative, absolute, or fixed).

3. Elements with a higher z-index value will appear on top of elements with a lower z-index value.

4. If two elements have the same z-index value, the element that appears later in the HTML code will be placed on top.

5. The z-index property only works on positioned elements in the same stacking context. In other words, if an element is positioned but has no z-index specified, it will be placed in the same stacking context as its parent element.

6. You can create a new stacking context by giving an element a z-index value other than "auto", along with a position value other than "static".

7. The z-index property can take both positive and negative values, with positive values bringing the element to the front and negative values sending it to the back.

8. The maximum and minimum values for the z-index property depend on the browser, but they typically range from -2147483648 to 2147483647.

9. When using z-index, it's important to consider the order in which elements appear in the HTML code and the positioning of their parent elements to avoid unexpected results.

10. Finally, it's important to use z-index sparingly and only when necessary, as it can easily lead to complex and difficult-to-maintain code if used excessively.

# Overflow

The CSS overflow property determines how content that exceeds the dimensions of a container element should be handled. It is a commonly used property in web design and can have several values:

1. visible - This is the default value. It allows content to overflow the container element and be visible outside of it.

2. hidden - This value hides any content that exceeds the dimensions of the container element. The content is clipped and not visible outside of the container.

3. scroll - This value adds a scrollbar to the container element, allowing the user to scroll through the content that exceeds the dimensions of the container. The scrollbar is visible even if there is no content to scroll.

4. auto - This value adds a scrollbar to the container element only if the content exceeds the dimensions of the container. If there is no content to scroll, the scrollbar is not visible.

The overflow property can be applied to any element, but it is most commonly used with block-level elements such as div and p. It is useful when you want to limit the height or width of an element and prevent its content from overflowing into other elements or causing layout issues.

It's important to note that the overflow property only affects the content inside the element and does not change the dimensions of the element itself. Therefore, if you want to limit the height or width of an element, you also need to use the height or width property.

Overall, the overflow property is a powerful tool in CSS that helps to manage the display of content in web design.

# Psedu-Classes

In CSS, pseudo-classes are used to style elements based on their state or position in the document tree. They are not part of the document itself, but rather are virtual elements that allow you to apply styles based on various conditions.

Here are some commonly used pseudo-classes:

1. :hover - This pseudo-class is used to apply styles to an element when the user hovers over it with their mouse.

2. :active - This pseudo-class is used to apply styles to an element when it is being clicked on or activated.

3. :focus - This pseudo-class is used to apply styles to an element when it has keyboard focus.

4. :visited - This pseudo-class is used to apply styles to a link that has been visited by the user.

5. :first-child - This pseudo-class is used to select the first child element of a parent element.

6. :last-child - This pseudo-class is used to select the last child element of a parent element.

7. :nth-child(n) - This pseudo-class is used to select the nth child element of a parent element. You can specify a specific number or a formula to select elements based on their position.

These are just a few examples of the many pseudo-classes available in CSS. They can be used in combination with other CSS selectors to create complex and specific styles for your web page. Pseudo-classes are a powerful tool in CSS that can greatly enhance the design and interactivity of your website.

# Pseudo-Elements

1. ::before - This pseudo-element allows you to insert content before the content of an element.

2. ::after - This pseudo-element allows you to insert content after the content of an element.

# TO-DO

[Building a rothko painting](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-the-css-box-model-by-building-a-rothko-painting/)

# Resources For TO-DO

[Building a rothko painting](https://www.youtube.com/watch?v=ZIcJDnavfdc)

# Class Assignment
- https://priyanshu-240499.github.io/Assignments-CSS/position/position.html 
