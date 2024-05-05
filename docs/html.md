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
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

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

</details>

<details >
<summary>
What is the difference between `<figure>` tag and `<img>` tag?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
Explain the importance of meta tags and their types.
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What are Sematic elements?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is difference between `<meter>` tag and `<progress>` tag?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is difference between SVG and Canvas HTML5 element?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
Explain the concept of web storage in HTML5.
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is comment in HTML and its type and usage?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What are the empty elements?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is the advantage of collapsing white space?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is hyperlink? What is its need?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is the need of alt tag in img tag?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is difference between HTML and XHTML?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is difference between absolute and relative URL?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is the role of action attribute in HTML forms?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is the role of method attribute in HTML forms?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
What is a marquee in HTML?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
 What is grouping tag in HTML?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>

<details >
<summary>
 What is accessibility in HTML?
</summary>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam fuga qui nesciunt ipsa eius laborum repudiandae aut dignissimos voluptatum, perspiciatis molestias numquam iste, dolores veniam. Aliquam, pariatur dolore quia non explicabo eius! Pariatur omnis quam quo molestias sequi, non quod consequatur beatae rem blanditiis inventore ratione quisquam aspernatur facere vel?

</details>
