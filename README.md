# htmlcssmajor1
hosted link of my mmain project:https://manuhegde198924.github.io/htmlcssmajor1/
for steps of my project refer:https://github.com/manuhegde198924/htmlcssmajor1/issues/1
some of important html elements used are:---->
nav: Defines a navigation section within a web page.

i: Marks text to be displayed in an italicized font style.

img: Embeds an image in a web page.

ul: Creates an unordered (bulleted) list.

li: Represents a list item within a list .
<section: Divides content into thematic sections within a web page, providing structure and organization.

<div: A generic container used to group and style elements for layout or other purposes.

<img: Embeds an image in a web page.

<span: A inline-level tag used for styling a specific portion of text within a larger block of content.
<h1: Defines the highest level of heading, usually used for the main title of a page or section.

<p: Represents a paragraph of text, used to structure and display blocks of content.

<span: An inline-level element used for applying styles or scripting to a specific portion of text within a larger content block.
<button: Represents a clickable button on a web page that can trigger actions or interactions, like submitting forms or executing JavaScript functions.
<form: Defines an HTML form that can contain various input elements and buttons, used to gather and submit user input to a server.

<label: Associates a label with a form element, providing a textual description or name for the input element it's associated with.

<input: Represents an input field within a form, allowing users to enter data such as text, numbers, or selections. The specific type of input is determined by attributes like type.
<a: Creates a hyperlink that links to another web page, resource, or location within the same page.

<img: Embeds an image in a web page.
: Defines a thematic grouping or section of content within a web page, often used to structure and organize content for better readability and semantics. 
important css selectors and proprties used in my project:------------->

visibility: Determines whether an element is visible or hidden. It accepts values "visible" (default), "hidden" (invisible but still takes up space), "collapse" (for table elements), and "inherit".

width: Sets the width of an element. It can be specified in various units like pixels (px), percentages (%), ems (em), and more.

background-color: Sets the background color of an element.

opacity: Specifies the transparency level of an element, ranging from 0 (completely transparent) to 1 (fully opaque).

display: Determines how an element is displayed, such as block (default, takes full width), inline (fits within content), and flex (enables flexible box layout).

flex-direction: Specifies the direction of flex items within a flex container, like row (horizontal, default) or column (vertical).

align-items: Aligns flex items along the cross-axis of a flex container.

padding: Sets the space between an element's content and its border.

box-shadow: Adds a shadow effect to an element.

margin-top: Sets the space above an element.

position: Specifies the positioning method of an element, like sticky, absolute, relative, and more.

top: Sets the distance an element's top edge is offset from its containing element.

left: Sets the distance an element's left edge is offset from its containing element.

z-index: Determines the stacking order of elements on the z-axis.

font-size: Sets the size of the font within an element.

text-decoration: Adds visual effects to text, such as underlines, overlines, and more.

color: Sets the color of text or other elements.

letter-spacing: Adjusts the spacing between characters in text.
- transition 

- transform effect
To create a transition effect, you must specify two things:

    the CSS property you want to add an effect to
    the duration of the effect

Note: If the duration part is not specified, the transition will have no effect, because the default value is 0.

The following example shows a 100px * 100px red <div> element. The <div> element has also specified a transition effect for the width property, with a duration of 2 seconds:
Example
div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s;
}

The transition effect will start when the specified CSS property (width) changes value.

Now, let us specify a new value for the width property when a user mouses over the <div> element:
Example
div:hover {
  width: 300px;
}

Notice that when the cursor mouses out of the element, it will gradually change back to its original style.
Change Several Property Values

The following example adds a transition effect for both the width and height property, with a duration of 2 seconds for the width and 4 seconds for the height:
Example
div {
  transition: width 2s, height 4s;
}
ADVERTISEMENT
Specify the Speed Curve of the Transition

The transition-timing-function property specifies the speed curve of the transition effect.

The transition-timing-function property can have the following values:

    ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
    linear - specifies a transition effect with the same speed from start to end
    ease-in - specifies a transition effect with a slow start
    ease-out - specifies a transition effect with a slow end
    ease-in-out - specifies a transition effect with a slow start and end
    cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function

The following example shows some of the different speed curves that can be used:
Example
#div1 {transition-timing-function: linear;}
#div2 {transition-timing-function: ease;}
#div3 {transition-timing-function: ease-in;}
#div4 {transition-timing-function: ease-out;}
#div5 {transition-timing-function: ease-in-out;}
Delay the Transition Effect

The transition-delay property specifies a delay (in seconds) for the transition effect.

The following example has a 1 second delay before starting:
Example
div {
  transition-delay: 1s;
}
Transition + Transformation

The following example adds a transition effect to the transformation:
Example
div {
  transition: width 2s, height 2s, transform 2s;
}
More Transition Examples

The CSS transition properties can be specified one by one, like this:
Example
div {
  transition-property: width;
  transition-duration: 2s;
  transition-timing-function: linear;
  transition-delay: 1s;
}

or by using the shorthand property transition:
Example
div {
  transition: width 2s linear 1s;
}
Test Yourself With Exercises
Exercise:

Add a 2 second transition effect for width changes of the <div> element.

<style>
div {
  width: 100px;
  height: 100px;
  background: red;
  : ;
}

div:hover {
  width: 300px;
}
</style>

<body>
  <div>This is a div</div>
</body>


padding-bottom: Sets the spacing at the bottom of an element's content area. It defines the space between the content and the element's bottom border.

width: Sets the width of an element.

height: Sets the height of an element.

display: Specifies the type of box used for an HTML element. In this case, it's set to flex to enable flex layout.

justify-content: Aligns flex items along the main axis of a flex container, in this case, centering them horizontal

transition 	A shorthand property for setting the four transition properties into a single property
transition-delay 	Specifies a delay (in seconds) for the transition effect
transition-duration 	Specifies how many seconds or milliseconds a transition effect takes to complete
transition-property 	Specifies the name of the CSS property the transition effect is for
transition-timing-function 	Specifies the speed curve of the transition effect


transition: Specifies the duration and properties that will transition smoothly when changed.

list-style-type: Sets the marker style for list items.
transition: Specifies the duration and properties that will transition smoothly when changed.

line-height: Sets the height of a line of text within an element.

margin-top: Sets the top margin of an element.

opacity: Sets the transparency level of an element, ranging from 0 (completely transparent) to 1 (fully opaque).

hover: Pseudo-class that applies styles when an element is hovered over by the cursor.
isplay: Specifies the type of box used for an HTML element. In this case, it's set to flex to enable a flex layout.

padding: Sets the spacing inside an element's content area.

justify-content: Aligns flex items along the main axis of a flex container, distributing the space evenly between them.

text-decoration: Sets the decoration added to text, such as underlines or strikes.

color: Sets the color of text or other elements.

font-size: Sets the size of the font within an element.

gap: Sets the spacing between elements within a container, such as a flex container or grid.

flex-wrap: Specifies whether flex items should wrap to a new line or not within a flex container.

width: Sets the width of an element.

height: Sets the height of an element.

object-fit: Specifies how an image should be resized to fit its container.

border-radius: Specifies the radius of an element's corners.

border: Sets the border of an element.
What is Responsive Web Design?

Responsive web design makes your web page look good on all devices.

Responsive web design uses only HTML and CSS.

Responsive web design is not a program or a JavaScript.
Designing For The Best Experience For All Users

Web pages can be viewed using many different devices: desktops, tablets, and phones. Your web page should look good, and be easy to use, regardless of the device.

Web pages should not leave out information to fit smaller devices, but rather adapt its content to fit any device:


Desktop

Tablet

Phone

It is called responsive web design when you use CSS and HTML to resize, hide, shrink, enlarge, or move the content to make it look good on any screen.
Using The width Property

If the width property is set to a percentage and the height property is set to "auto", the image will be responsive and scale up and down:
Example
img {
  width: 100%;
  height: auto;
}

Notice that in the example above, the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the max-width property instead.
Using The max-width Property

If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size:
Example
img {
  max-width: 100%;
  height: auto;
}
Add an Image to The Example Web Page
Example
img {
  width: 100%;
  height: auto;
}
ADVERTISEMENT
Background Images

Background images can also respond to resizing and scaling.

Here we will show three different methods:

1. If the background-size property is set to "contain", the background image will scale, and try to fit the content area. However, the image will keep its aspect ratio (the proportional relationship between the image's width and height):

Here is the CSS code:
Example
div {
  width: 100%;
  height: 400px;
  background-image: url('img_flowers.jpg');
  background-repeat: no-repeat;
  background-size: contain;
  border: 1px solid red;
}

2. If the background-size property is set to "100% 100%", the background image will stretch to cover the entire content area:

Here is the CSS code:
Example
div {
  width: 100%;
  height: 400px;
  background-image: url('img_flowers.jpg');
  background-size: 100% 100%;
  border: 1px solid red;
}

3. If the background-size property is set to "cover", the background image will scale to cover the entire content area. Notice that the "cover" value keeps the aspect ratio, and some part of the background image may be clipped:

Here is the CSS code:
Example
div {
  width: 100%;
  height: 400px;
  background-image: url('img_flowers.jpg');
  background-size: cover;
  border: 1px solid red;
}
Different Images for Different Devices

A large image can be perfect on a big computer screen, but useless on a small device. Why load a large image when you have to scale it down anyway? To reduce the load, or for any other reasons, you can use media queries to display different images on different devices.

Here is one large image and one smaller image that will be displayed on different devices:
Example
/* For width smaller than 400px: */
body {
  background-image: url('img_smallflower.jpg');
}

/* For width 400px and larger: */
@media only screen and (min-width: 400px) {
  body {
    background-image: url('img_flowers.jpg');
  }
}

You can use the media query min-device-width, instead of min-width, which checks the device width, instead of the browser width. Then the image will not change when you resize the browser window:
Example
/* For devices smaller than 400px: */
body {
  background-image: url('img_smallflower.jpg');
}

/* For devices 400px and larger: */
@media only screen and (min-device-width: 400px) {
  body {
    background-image: url('img_flowers.jpg');
  }
}
The HTML <picture> Element

The HTML <picture> element gives web developers more flexibility in specifying image resources.

The most common use of the <picture> element will be for images used in responsive designs. Instead of having one image that is scaled up or down based on the viewport width, multiple images can be designed to more nicely fill the browser viewport.

The <picture> element works similar to the <video> and <audio> elements. You set up different sources, and the first source that fits the preferences is the one being used:
Example
<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 400px)">
  <source srcset="img_flowers.jpg">
  <img src="img_flowers.jpg" alt="Flowers">
</picture>

The srcset attribute is required, and defines the source of the image.

The media attribute is optional, and accepts the media queries you find in CSS @media rule.

You should also define an <img> element for browsers that do not support the <picture> element.
The viewport is the user's visible area of a web page.

The viewport varies with the device, and will be smaller on a mobile phone than on a computer screen.

Before tablets and mobile phones, web pages were designed only for computer screens, and it was common for web pages to have a static design and a fixed size.

Then, when we started surfing the internet using tablets and mobile phones, fixed size web pages were too large to fit the viewport. To fix this, browsers on those devices scaled down the entire web page to fit the screen.

This was not perfect!! But a quick fix.
Setting The Viewport

HTML5 introduced a method to let web designers take control over the viewport, through the <meta> tag.

You should include the following <meta> viewport element in all your web pages:
<meta name="viewport" content="width=device-width, initial-scale=1.0">

This gives the browser instructions on how to control the page's dimensions and scaling.

The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

Here is an example of a web page without the viewport meta tag, and the same web page with the viewport meta tag:



Without the viewport meta tag



With the viewport meta tag

Tip: If you are browsing this page with a phone or a tablet, you can click on the two links above to see the difference.
Size Content to The Viewport

Users are used to scroll websites vertically on both desktop and mobile devices - but not horizontally!

So, if the user is forced to scroll horizontally, or zoom out, to see the whole web page it results in a poor user experience.

Some additional rules to follow:

1. Do NOT use large fixed width elements - For example, if an image is displayed at a width wider than the viewport it can cause the viewport to scroll horizontally. Remember to adjust this content to fit within the width of the viewport.

2. Do NOT let the content rely on a particular viewport width to render well - Since screen dimensions and width in CSS pixels vary widely between devices, content should not rely on a particular viewport width to render well.

3. Use CSS media queries to apply different styling for small and large screens - Setting large absolute CSS widths for page elements will cause the element to be too wide for the viewport on a smaller device. Instead, consider using relative width values, such as width: 100%.
4.  Also, be careful of using large absolute positioning values.
5.  It may cause the element to fall outside the viewport on small devices.



