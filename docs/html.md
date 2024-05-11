---
sidebar_position: 1
---

# HTML

<details >
<summary>
What is difference between HTML tags, elements and attributes?
</summary>

### Html Elements:

An Html Element consists of an opening and closing tag with the content inserted in between:

For Example:

```html
<p>Content goes here...</p>
```

### Html tag:

The HTML tag is just an opening or closing entity.

For Example:

```html
<p></p>
```

![alt text](JFL1P.png)

### HTML attributes

An attribute defines a property for an element, consists of an attribute/value pair, and appears within the element’s start tag. An element’s start tag may contain any number of space separated attribute/value pairs.

```html
<a href="https://www.google.com">Visit Link</a>
```

</details>

<details >
<summary>
 What are HTML entities?
</summary>

### Entity

An HTML entity is a piece of text ("string") that begins with an ampersand (&) and ends with a semicolon (;). HTML entities are frequently used to display reserved characters (which would otherwise be interpreted as HTML code), and invisible characters (like non-breaking spaces). You can also use HTML character entities in place of other characters that are difficult to type with a standard keyboard.

### Reserved characters

Some special characters are reserved for use in HTML, meaning that your browser will parse them as HTML code. For example, if you use the less-than (<) sign, the browser interprets any text that follows as a tag.

To display these characters as text, replace them with their corresponding character entities.

```html
&amp;
<!-- Interpreted as the beginning of an entity or character reference '&' -->

&lt;
<!--Interpreted as the beginning of a  tag '<' -->

&gt;
<!--Interpreted as the ending of a tag '>' -->

&copy;
<!--Interpreted as the copyright sign '©'-->

&deg;
<!--Interpreted as the degree symbol '°'-->
```

</details>

<details >
<summary>
 What are different types of lists in HTML?
</summary>

## HTML List

HTML lists allow the content to follow a proper semantic structure. All the tags in the list require opening and closing tags.
There are 3 types of lists in HTML, namely:

- Unordered List
- Ordered List
- Description List

### Unordered list

Unordered List: An Unordered list is used to create a list of related items, in bulleted or unordered format.

```html
<ul>
  <li>Item1</li>
  <li>Item2</li>
  <li>Item3</li>
  ...
</ul>
```

## Ordered lists

The Ordered lists have an order which is either numerical or alphabetical.

```html
<ol>
  <li>Item1</li>
  <li>Item2</li>
  <li>Item3</li>
  ...
</ol>
```

## Description List

A description list is a type of list where each item has a description. It is also known as a definition list.

```html
<dl>
  <!--<dl>: It defines the start of the list.-->
  <dt>Code</dt>
  <!--<dt>: It defines a item.-->
  <dd>- Code all day!</dd>
  <!--<dd>: It defines the description of each item.-->
  <dt>Eat</dt>
  <dd>- Eat healthy food</dd>
  <dt>Sleep</dt>
  <dd>- Sleep soundly!</dd>
</dl>
```

</details>

<details >
<summary>
What is difference between “id attribute” and the “class attribute” of HML elements?
</summary>

In HTML, the "id" and "class" attributes are used to identify and style elements, but they have different purposes.

The "id" attribute is used to uniquely identify an element on a web page. Each "id" value should be unique within the HTML document. It is often used to target specific elements with CSS or JavaScript for styling or functionality.

On the other hand, the "class" attribute is used to group together elements that share a common purpose or style. Multiple elements can have the same "class" value, allowing them to be styled or targeted as a group using CSS or JavaScript.

In summary, "id" is used to uniquely identify a single element, while "class" is used to group multiple elements together.

</details>

<details >
<summary>
List various types of formatting tags in HTML with example.
</summary>

- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<strike>` - strike text
- `<u>` - underline text
- `<sub>` - Subscript text
- `<sup>` - Superscript text
- `<big>` - Big text (1 unit of base text size)
- `<small>` - Smaller text
- `<tt>` - browser's default monospace text

```html
<!--Text in Bold-->
<p><b>Bold Text</b></p>

<!--Text in Strong-->
<p><strong> Strong Text</strong></p>

<!--Text in Italics-->
<p><i>The Text inside italic Tag</i></p>

<!--Text in Emphasize-->
<p><em>Emphasized Text</em></p>

<!-- small text -->
<small>The text inside small Tag</small>

<!-- Big text-->
<big>The text inside big Tag</big>

<!--Text in Superscript-->
superscript <sup>Text</sup>

<!--Text in Subscript-->
subscript<sub>Text</sub>

<!--Deleting andText in Insert-->
<p>
  The TajMahal is located in
  <del>Bombay</del>
  <ins>Agra</ins>
</p>

<!--Text in Highlight-->
<mark>Highlighted Text</mark>

<!-- monospace text -->
<tt>Monospace text</tt>

<!-- underline text -->
<u>underline text</u>
```

</details>

<details >
<summary>
Explain the usage of `<!DOCTYPE>` in HTML.
</summary>

### `<!DOCTYPE>`

tag is used to inform the browser about the version of HTML used in the document. It is called as the document type declaration (DTD). Technically <! DOCTYPE > is not a tag/element, it just an instruction to the browser about the document type.

</details>

<details >
<summary>
What is the significance of the `<head>` and `<body>` tag?
</summary>

## `<head>` tag:

The head tag in HTML is used to contain the metadata or information related to the document. It holds some of the most important tags like `<title>` , `<meta>` , and `<link>`.

- From browser perspective, it is not mandatory to include a `<head>` tag inside the HTML document but in previous versions(4.0.1) it was mandatory to include it.

- The tags like `<title>`, `<meta>` or `<link>` which are generally contained inside head will also work fine without the `<head>` tag or outside the `<head>` tag.

- From the developer’s perspective, it is good to include the `<head>` tag inside the document because this syntax is widely used and it also gives a good structure to the document. Later this will help us to interact with the DOM elements in a structured way.

## `<body>` tag:

It is used to contain the main content of the HTML document. It holds everything from the heading, paragraphs to the unique div containers reside inside the `<body>` tag.

- From browser perspective, it is also not mandatory to include a <body> tag inside the HTML document in HTML 5 but in previous versions(4.0.1) it was mandatory to include it.

- The tags like `<div>`, `<p>` or `<a>` which are generally contained inside body will also work fine without the `<body>` tag or outside the `<body>` tag.
  Despite being not mandatory, the `<body>` tag have some attributes like ‘background’, ‘bgcolor’ , ‘a’ , ‘link’ etc.

- From the developer’s perspective, it is good to include the `<body>` tag inside the document. This syntax is widely used and it also gives a good structure to the document. Later this will help us to interact with the DOM elements in a structured way.

</details>

<details >
<summary>
 State the difference between inline and block element.
</summary>

## Block elements:

They consume the entire width available irrespective of their sufficiency. They always start in a new line and have top and bottom margins. It does not contain any other elements next to it.

#### Examples of Block elements:

- `<h1>-<h6>`
- `<div>`
- `<hr>`
- `<li>`
- `<ul>`
- `<ol>`
- `<p>`
- `<table>`

#### Semantic block elements:

- `<header>`
- `<main>`
- `<section> `
- `<footer>`
- `<nav>`
- `<article>`
- `<aside>`

## Inline elements:

Inline elements occupy only enough width that is sufficient to it and allows other elements next to it which are inline. Inline elements don’t start from a new line and don’t have top and bottom margins as block elements have.

#### Examples of Inline elements:

- `<a>`
- `<b>`
- `<br>`
- `<script>`
- `<input>`
- `<img>`
- `<span>`
- `<label>`
</details>

<details >
<summary>
What is the difference between `<link>` and `<a.>`  tag?
</summary>

## `<link>` Tag:

This tag is used to establish a connection/relationship between the current document and some external resources that are associated with the webpage. The resource could be a CSS file, an icon used in the site, a manifest, etc.

It has certain attributes some of mostly used are the following.

- href= "URL"
- media= "media_query/media_type"
- rel= "relationship_with_resource"
- size= "HeightxWidth"
- type= "MIME_TYPE"

### Example:

```html
<html>
  <head>
    <title>Link Tag</title>
    <link rel="stylesheet" href="./externalResource.css" />
  </head>
  <body></body>
</html>
```

## `<a>` Tag:

This anchor tag establishes a hyperlink to an external or internal document of HTML, an address like email or telephone, and some kind of external URL address.

### Some of the commonly used attributes are:-

- href="URL"
- target="some_browsing_context"
- download="filename.ext"
- ping="URL"

### Example:

```html
<a href="https://www.google.com" target="_blank"> anchor tag </a>
```

</details>

<details >
<summary>
What is differences between the HTML vs HTML5.
</summary>

- HTML

HTML stands for Hyper Text Markup Language. It is used to design web pages using a markup language. HTML is a combination of Hypertext and Markup language

- HTML5

HTML 5 is the fifth and current version of HTML. It has improved the markup available for documents and has introduced application programming interfaces(API) and Document Object Model(DOM). It has introduced various new features like drag and drop, geo-location services

<table>
<col>
<col>
<thead>
<tr>
<th>HTML</th>
<th>HTML5</th>
</tr>
</thead>
<tbody>
<tr>
<td>It didn’t support audio and video without the use of flash player support.</td>
<td >It supports audio and video controls with the use of &lt;audio&gt; and &lt;video&gt; tags.</td>
</tr>
<tr>
<td>It uses cookies to store temporary data.td>
<td >It uses SQL databases and application cache to store offline data.</td>
</tr>
<tr>
<td >Does not allow JavaScript to run in the browser.</span></td>
<td >Allows JavaScript to run in the background. This is possible due to JS Web worker API in HTML5.</td>
</tr>
<tr>
<td >Vector graphics are possible in HTML with the help of various technologies such as VML, Silver-light, Flash, etc.</td>
<td >Vector graphics are additionally an integral part of HTML5 like SVG and Canvas.</td>
</tr>
<tr>
<td >It does not allow drag and drop effects.</td>
<td >It allows drag and drop effects.</td>
</tr>

<tr>
<td >It works with all old browsers.</td>
<td >It supported by all new browser like Firefox, Mozilla, Chrome, Safari, etc.</td>
</tr>
<tr>
<td >&lt;HTML&gt;,&lt;Body&gt; , and &lt;Head&gt; tags are mandatory while writing a HTML code.</td>
<td >These tags can be omitted while writing HTML code.</td>
</tr>

<tr>
<td >Elements like nav, header were not present.</td>
<td >New element for web structure like nav, header, footer etc.</td>
</tr>

<tr>
<td >It is almost impossible to get true GeoLocation of user with the help of browser.</td>
<td >One can track the GeoLocation of a user easily by using JS GeoLocation API.</td>
</tr>

</tbody>
</table>
</table>

</details>

<details >
<summary>
What is forms in HTML?
</summary>

HTML Form is a document that stores information of a user on a web server using interactive controls. An HTML form contains different kinds of information such as username, password, contact number, email id, etc.
The elements used in an HTML form are the check box, input box, radio buttons, submit buttons, etc. Using these elements the information of a user is submitted on a web server.

Example:

```html
<!DOCTYPE html>
<html>
  <body>
    <form>
      Username:<br />
      <input type="text" name="username" />
      <br />
      Email id:<br />
      <input type="text" name="email_id" />
      <br /><br />
      <input type="submit" value="Submit" />
    </form>
  </body>
</html>
```

</details>

<details >
<summary>
Explain the types of inputs in HTML with example.

</summary>

The `<input>` HTML element is used to create interactive controls for web-based forms in order to accept data from the user.

How an `<input>` works varies considerably depending on the value of its type attribute. If this attribute is not specified, the default type adopted is text.

- button: A push button with no default behavior displaying the value of the value attribute, empty by default.

```html
<label for="button">input button</label>
<input type="button" id="button" name="button" />
```

- checkbox: A check box allowing single values to be selected/deselected.

```html
<div>
  <input type="checkbox" id="scales" name="scales" checked />
  <label for="scales">Scales</label>
</div>

<div>
  <input type="checkbox" id="horns" name="horns" />
  <label for="horns">Horns</label>
</div>
```

- color:Interface used to choose the color of our choice.

```html
  <input type="color" id="head" name="head" value="#e66465" />
  <label for="head">Head</label>
</div>
```

- date: Interface used to choose a date.

```html
<input
  type="date"
  id="start"
  name="trip-start"
  value="2018-07-22"
  min="2018-01-01"
  max="2018-12-31"
/>
```

- Email: Interface used to accept e-mail addresses.

```html
<input type="email" id="email" pattern=".+@example\.com" size="30" required />
```

- File: Interface used to upload files.

```html
<input type="file" id="avatar" name="avatar" accept="image/png, image/jpeg" />
```

- Image: Interface used to input an image.

```html
<input
  type="image"
  id="image"
  alt="Login"
  src="/media/examples/login-button.png"
/>
```

- Month: Interface used to input years and months. The format is “YYYY-MM”.

```html
<input type="month" id="start" name="start" min="2018-03" value="2018-05" />
```

- Number: Interface let the user enter a number.

```html
<input type="number" id="tentacles" name="tentacles" min="10" max="100" />
```

- Password: Interface defines a password field (characters are masked for security).

```html
<label for="pass">Password (8 characters minimum):</label>
<input type="password" id="pass" name="password" minlength="8" required />
```

- Radio: Collection of radio buttons inputting a set of options.

```html
<input type="radio" id="huey" name="drone" value="huey" checked />
<label for="huey">Huey</label>

<input type="radio" id="dewey" name="drone" value="dewey" />
<label for="dewey">Dewey</label>

<input type="radio" id="louie" name="drone" value="louie" />
<label for="louie">Louie</label>
```

- Range: Slide control interface with Default range is 0 to 100.

```html
<input type="range" id="volume" name="volume" min="0" max="11" />
<label for="volume">Volume</label>
```

- Reset :Interface used to resets the form to the default values.

```html
<label for="id">User ID:</label>
<input type="text" id="id" name="id" />

<input type="reset" value="Reset" />
<input type="submit" value="Submit" />
```

- Search: Interface for entering a search string.

```html
<input type="search" id="site-search" name="q" />

<button>Search</button>
```

- Submit: Interface for submitting all form values to a form-handler.

```html
<input type="submit" value="Send Request" />
```

- URL: elements of type url are used to let the user enter and edit a URL.

```html
<label for="url">Enter an https:// URL:</label>
<input
  type="url"
  name="url"
  id="url"
  placeholder="https://example.com"
  pattern="https://.*"
  size="30"
  required
/>
```

</details>

<details >
<summary>
What is the difference between `<figure>` tag and `<img>` tag?
</summary>
 
`<figure>` tag is used to semantically organize the content of images, videos, audios or even charts or tables, block of codes in the HTML document.

```html
<figure>
  <img src="url" />
  <figcaption>content</figcaption>
</figure>
```

figcaption: This tag is used to set the caption to the image. It is optional to use.

HTML `<img>` tag is used to add image or to set the background in the webpage/website. Nowadays website does not directly add images to a web page, as the images are linked to web pages by using the `<img>` tag which holds space for the image.

```html
<img src="url" alt="some_text" />
```

</details>

<details >
<summary>
Explain the importance of meta tags and their types.
</summary>

Meta tags are pieces of information you use to tell the search engines and those viewing your site more about your page and the information it contains. Meta tags include:

- Title tags: the title of your page, which should be unique for every page you publish
- Meta description: a description of the content on the page
- Viewport tag: impacts how your content appears on mobile devices

- Robots: can be used to indicate content that you want a “noindex” or a “nofollow”
- Hreflang tags: allows the search engine to identify the language and country you want content displayed for when you have an international audience
- Canonical tags: used to specify the primary or principle version of the page
- Open graph tags: used to specify which assets show up in title and image by default when sharing links on social sites
- Content type: impacts how your page is rendered in the browser

Meta tags are brief snippets of text designed to describe a page’s content. these tags do not appear visibly on the page; rather, they are embedded in the page’s source code. Search engines are the ones that read and interpret these tags, aiding them in comprehending the subject matter of the page.

</details>

<details >
<summary>
What are Sematic elements?
</summary>
A semantic element clearly describes its meaning to both the browser and the developer.

Examples of non-semantic elements: `<div>` and `<span>` - Tells nothing about its content.

Examples of semantic elements: `<form>`, `<table>`, and `<article>` - Clearly defines its content.

</details>

<details >
<summary>
What is difference between `<meter>` tag and `<progress>` tag?
</summary>

- Progress tag: This tag is used to represent a progress bar on the webpage in order to show the progress of a task. Some uses of the progress bar include showing the file upload/download progress on a website.

```html
<progress value="50" max="200"></progress>
```

- Meter Tag: A Meter tag is also known as a gauge and basically defines a scale for the measurement of data within a specified range. The uses of a meter tag may include the fuel left in the tank, the temperature of an object, etc.

```html
<meter value="50" max="200" min="20"></meter>
```

</details>

<details >
<summary>
What is difference between SVG and Canvas HTML5 element?
</summary>

- Scalable Vector Graphics (SVG) is an XML-based image format used to define two-dimensional vector-based graphics for the web. Unlike raster images (Ex .jpg, .gif, .png, etc.),
  a vector image can be scaled up or down to any extent without losing the image quality. An SVG image is drawn out using a series of statements that follow the XML schema — that means SVG images can be created and edited with any text editor, such as Notepad.

```html
<svg id="svgelem" height="200">
  <circle id="greencircle" cx="60" cy="60" r="50" fill="green" />
</svg>
```

- The Canvas element is used to draw graphics on the fly, via scripting (usually JavaScript). The element is only a container for graphics. You must use a script to actually draw the graphics. Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

```html
<canvas
  id="newCanvas"
  width="100"
  height="100"
  style="border:1px solid #000000;"
>
</canvas>

<script>
  var c = document.getElementById("newCanvas");
  var ctx = c.getContext("2d");
  ctx.fillStyle = "#7cce2b";
  ctx.fillRect(0, 0, 100, 100);
</script>
```

</details>

<details >
<summary>
Explain the concept of web storage in HTML5.
</summary>

In web storage feature, web applications can locally store data within the browser on the client side. It stores data in the form of key/value pair on the browser. Web Storage sometimes also known as DOM storage.

Storing data with the help of web storage is similar to cookies, but it is better and faster than cookies storage.

Advantages of Web Storage:

- Web Storage can use storage space upto 5MB per domain. (The browser software may prompt the user if the space limit is reached).
- It will not send data to the server side, hence it is faster than cookies storage.
- The data stored by local Storage never expires, but cookies data expires after some time or session.
- Web Storage is more secure than cookies.

</details>

<details >
<summary>
What is comment in HTML and its type and usage?
</summary>

The comment tag is used to insert comments in the source code.
Comments are not displayed in the browsers.

You can use comments to explain your code, which can help you when you edit the source code at a later date.

Types of HTML Comments

1. Single line Comments in HTML

```html
<!--following is a paragraph-->
<p><i>Welcome to DataFlair!</i></p>
```

2. Multi-line Comments in HTML

```html
<!--Comments can be used to
add multiple line
on to the HTML Document.-->
<!--following is a paragraph-->
<p>Welcome to DataFlair</p>
```

3. `<comment>` tag in HTML

```html
<p>
  This is <comment>not</comment>
  Internet Explorer.
</p>
```

4. Conditional Comments in HTML

```html
<!--[if IE 9]>
  <h1>DataFlair</h1>
  <p>E-Learning</p>
<![endif]-->
```

</details>

<details >
<summary>
What are the empty elements?
</summary>

Empty or void elements are HTML elements that don’t require a closing tag because they contain no content. They are self-contained, independently complete, and don’t rely on other elements to function. Instead of having separate open and closing tags, empty elements combine both into a single tag, making it easy to add certain types of content to a page.

You can use empty HTML elements to add structure and functionality to web pages, such as embedding images, links, breaks, lists, or metadata.

</details>

<details >
<summary>
What is the advantage of collapsing white space?
</summary>

In HTML, a sequence of whitespace characters is treated as a single space character.

The browser collapses a sequence of spaces into a single space character, which helps a developer indent the HTML code as needed for better readability and understandability without worrying about the extra spaces within the HTML code.

```html
<!DOCTYPE html>
<html>
  <head> </head>
  <body>
    <h1>HTML Collapses Extra Space</h1>
    <p>
      Paragraph content has a sequence of spaces that are collapsed to a single
      space character by the browser.
    </p>
  </body>
</html>
```

</details>

<details >
<summary>
What is hyperlink? What is its need?
</summary>

A hyperlink, also called a link or web link, contains an address for a destination and acts as a reference to data. A user can easily follow, jump to, and be directed to the destination by either clicking, tapping on, or hovering over the link.

A hyperlink can be a piece of text, an image, an icon, or a graphic that, when you click on it, points to and navigates you to a different webpage or document. It can also point to a specific section or element within the same webpage or document.

Hypertext is text with hyperlinks. The linked text (the reference to data) is called anchor text.

```html
<a href="https://www.google.com/"> click to link</a>
```

</details>

<details >
<summary>
What is the need of alt tag in img tag?
</summary>

The alt attribute provides alternative information for an image if a user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

```html
<img scr="img_girl.jpg" alt="text" />
```

</details>

<details >
<summary>
What is difference between HTML and XHTML?
</summary>

HTML (HypertextMarkup Language) and XHTML (Extensible Hypertext Markup Language) are both markup languages used for creating and displaying web pages. The main difference between them is the syntax and structure; HTML is more lenient in its syntax, while XHTML has a more strict syntax and follows XML rules.

#### Key Differences Between HTML and XHTML

- Syntax: XHTML has a stricter syntax than HTML, meaning that it must follow XML rules for proper formatting and structure. HTML, on the other hand, is more flexible in its syntax.

- Document Type Definition (DTD): XHTML requires a DTD to be specified, which defines the rules for the structure of the document. HTML does not require a DTD.

- Case sensitivity: XHTML is case sensitive, meaning that elements and attributes must be in lower case. HTML is not case sensitive.

- Empty Elements: In XHTML, all empty elements must be closed, such as `<br />` or `<img src="image.jpg" alt="image" />`. In HTML, some empty elements can be left open, such as `<br>` or `<img src="image.jpg" alt="image">`.

- Attribute values: In XHTML, all attribute values must be quoted, while in HTML they can be either quoted or unquoted.

- Error handling: XHTML has more strict error handling, with errors resulting in the page not being displayed properly. HTML is more forgiving of errors and will still display the page even if there are mistakes in the code.

- Future compatibility: XHTML is designed to be compatible with future technologies and devices, while HTML may not be as compatible in the future.

</details>

<details >
<summary>
What is difference between absolute and relative URL?
</summary>

Absolute URLs specify the full path to a resource including the protocol and domain name, while relative URLs specify a path relative to the current URL’s base path.

- An absolute URL provides the complete address of a webpage or file on the internet, including the protocol “http:// or https://” domain, and path to the resource.

eg. https://www.example.com/images/logo.png

- A relative URL specifies the path to a resource about the current document’s path or the base URL of the website, without the domain name and protocol.

a relative URL to another page in the same directory like contact.html would simply be ,
e.g. contact.html

</details>

<details >
<summary>
What is the role of action attribute in HTML forms?
</summary>

The HTML action Attribute is used to specify where the form data is to be sent to the server after the submission of the form. When a user submits a form, the browser sends the data to the specified URL, allowing server-side scripts to handle the information and generate a response.

```html
<form action="URL"></form>
```

</details>

<details >
<summary>
What is the role of method attribute in HTML forms?
</summary>

The method attribute specifies how to send form-data (the form-data is sent to the page specified in the action attribute).

The form-data can be sent as URL variables (with method="get") or as HTTP post transaction (with method="post").

Notes on GET:

- Appends form-data into the URL in name/value pairs
- The length of a URL is limited (about 3000 characters)
- Never use GET to send sensitive data! (will be visible in the URL)
- Useful for form submissions where a user wants to bookmark the result
- GET is better for non-secure data, like query strings in Google

Notes on POST:

- Appends form-data inside the body of the HTTP request (data is not shown in URL)
- Has no size limitations
- Form submissions with POST cannot be bookmarked

</details>

<details >
<summary>
What is a marquee in HTML?
</summary>

The `<marquee>` HTML element is used to insert a scrolling area of text. You can control what happens when the text reaches the edges of its content area using its attributes.

## Attributes

- behavior: Sets how the text is scrolled within the marquee. Possible values are scroll, slide and alternate. If no value is specified, the default value is scroll.

- bgcolor: Deprecated Sets the background color through color name or hexadecimal value.

- direction: Deprecated Sets the direction of the scrolling within the marquee. Possible values are left, right, up and down. If no value is specified, the default value is left.

- height: Deprecated Sets the height in pixels or percentage value.

- hspace: Deprecated
  Sets the horizontal margin

- loop: Deprecated
  Sets the number of times the marquee will scroll. If no value is specified, the default value is −1, which means the marquee will scroll continuously.

- scrollamount: Deprecated
  Sets the amount of scrolling at each interval in pixels. The default value is 6.

- scrolldelay: Deprecated
  Sets the interval between each scroll movement in milliseconds. The default value is 85.

- truespeed: Deprecated
  By default, scrolldelay values lower than 60 are ignored. If truespeed is present, those values are not ignored.

- vspace: Deprecated
  Sets the vertical margin in pixels or percentage value.
- width: Deprecated
  Sets the width in pixels or percentage value.

```html
<marquee>This text will scroll from right to left</marquee>

<marquee direction="up">This text will scroll from bottom to top</marquee>

<marquee
  direction="down"
  width="250"
  height="200"
  behavior="alternate"
  style="border:solid"
>
  <marquee behavior="alternate">This text will bounce</marquee>
</marquee>
```

</details>

<details >
<summary>
 What is grouping tag in HTML?
</summary>

Grouping plays a vital role in our web page because it helps the developer to target specific classes and id which makes it easier to position, style, or manipulate the web page with the help of HTML, CSS, or JavaScript.

Grouping can be performed with the help of various tags such as `<div>`, `<header>`, `<footer>`, and `<section>`.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      header {
        color: red;
      }

      .div1 {
        background: yellow;
      }

      .div2 {
        background: blue;
      }

      footer {
        color: blue;
      }
    </style>
  </head>

  <body>
    <header>
      <h1>This is heading</h1>

      <p>This is paragraph in header group</p>
    </header>

    <div class="div1">
      <h1>In Div1</h1>
    </div>
    <div class="div2">
      <h1>In Div2</h1>
    </div>

    <footer>
      <p>This is footer information</p>

      <p><a href="mailto:xyz@gmail.com">Email</a></p>
    </footer>
  </body>
</html>
```

</details>

<details >
<summary>
 What is accessibility in HTML?
</summary>

Accessibility is the practice of making your websites usable by as many people as possible. We traditionally think of this as being about people with disabilities, but the practice of making sites accessible also benefits other groups such as those using mobile devices, or those with slow network connections.

Some common accessibility considerations in HTML include:

- Semantic HTML, which improves accessibility, also improves SEO, making your site more findable.

- Caring about accessibility demonstrates good ethics and morals, which improves your public image.

- Text Alternatives: Providing descriptive text alternatives for non-text content such as images, videos, and audio files using the alt attribute for images (`<img>`), `<audio>` and `<video>` elements.

- Form Accessibility: Providing labels for form inputs, using appropriate input types (`<input type="text">`, `<input type="email">`, `<input type="checkbox">`, etc.), and associating labels with their corresponding inputs using the for attribute on `<label>` elements.

- Other good practices that improve accessibility also make your site more usable by other groups, such as mobile phone users or those on low network speed. In fact, everyone can benefit from many such improvements.

</details>
```
