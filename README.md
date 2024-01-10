# HTML Tutorial

This README provides a comprehensive overview of HTML, covering various elements, tags, and concepts.

## Table of Contents

- [HTML](#html)
- [HTML Elements](#html-elements)
- [HTML Tags](#html-tags)
- [The `<!DOCTYPE>` Declaration](#the-doctype-declaration)
- [HTML Page Structure](#html-page-structure)
- [HTML Headings](#html-headings)
- [HTML Paragraphs](#html-paragraphs)
- [HTML Links](#html-links)
- [HTML Images](#html-images)
- [HTML Buttons](#html-buttons)
- [HTML Lists](#html-lists)
- [HTML Tables](#html-tables)
- [HTML Forms](#html-forms)
- [HTML Iframes](#html-iframes)
- [HTML Colors](#html-colors)
- [HTML CSS](#html-css)
- [HTML JavaScript](#html-javascript)
- [HTML File Paths](#html-file-paths)
- [HTML Head](#html-head)
- [HTML Layout Elements](#html-layout-elements)
- [HTML Styles](#html-styles)
- [HTML Formatting](#html-formatting)
- [HTML Quotations](#html-quotations)
- [HTML Comments](#html-comments)
- [HTML Classes](#html-classes)
- [HTML Id](#html-id)
- [HTML Blocks](#html-blocks)
- [HTML Multimedia](#html-multimedia)
  - [HTML Canvas](#html-canvas)
  - [HTML Audio](#html-audio)
  - [HTML Video](#html-video)
- [HTML Embedding](#html-embedding)
  - [HTML Embed](#html-embed)
  - [HTML Object](#html-object)
- [HTML Semantic Elements](#html-semantic-elements)
  - [HTML Header & Footer](#html-header--footer)
  - [HTML Navigation & Section](#html-navigation--section)
  - [HTML Article & Aside](#html-article--aside)
  - [HTML Details & Summary](#html-details--summary)
- [HTML Forms (Advanced)](#html-forms-advanced)
  - [HTML Input Types](#html-input-types)
  - [HTML Form Validation](#html-form-validation)
- [HTML Metadata](#html-metadata)
  - [HTML Meta Tags](#html-meta-tags)
  - [HTML Base](#html-base)
- [HTML Scripting](#html-scripting)
  - [HTML Script](#html-script)
  - [HTML Noscript](#html-noscript)
- [HTML Media Attributes](#html-media-attributes)
  - [HTML Audio Attributes](#html-audio-attributes)
  - [HTML Video Attributes](#html-video-attributes)
- [HTML Responsive Design](#html-responsive-design)
  - [HTML Responsive Images](#html-responsive-images)
  - [HTML Responsive Tables](#html-responsive-tables)
- [HTML Accessibility](#html-accessibility)
  - [HTML Aria Attributes](#html-aria-attributes)
  - [HTML Figure and Figcaption](#html-figure-and-figcaption)
- [HTML SVG](#html-svg)
  - [HTML SVG Element](#html-svg-element)
- [HTML Web Components](#html-web-components)
  - [HTML Custom Elements](#html-custom-elements)
  - [HTML Template Element](#html-template-element)
- [HTML Storage](#html-storage)
  - [HTML Local Storage](#html-local-storage)
  - [HTML Session Storage](#html-session-storage)
- [HTML Forms (Advanced)](#html-forms-advanced-1)
  - [HTML Datalist](#html-datalist)
  - [HTML Meter](#html-meter)
  - [HTML Progress](#html-progress)
- [HTML Scripting (Continued)](#html-scripting-continued)
  - [HTML Script](#html-script)
  - [HTML Noscript](#html-noscript)
- [HTML Media Attributes (Continued)](#html-media-attributes-continued)
  - [HTML Audio Attributes](#html-audio-attributes)
  - [HTML Video Attributes](#html-video-attributes)
- [HTML Responsive Design (Continued)](#html-responsive-design-continued)
  - [HTML Responsive Images](#html-responsive-images)
  - [HTML Responsive Tables](#html-responsive-tables)
- [HTML Accessibility (Continued)](#html-accessibility-continued)
  - [HTML Aria Attributes](#html-aria-attributes)
  - [HTML Figure and Figcaption](#html-figure-and-figcaption)
- [HTML SVG (Continued)](#html-svg-continued)
  - [HTML SVG Element](#html-svg-element)
- [HTML Web Components (Continued)](#html-web-components-continued)
  - [HTML Custom Elements](#html-custom-elements)
  - [HTML Template Element](#html-template-element)
- [HTML Storage (Continued)](#html-storage-continued)
  - [HTML Local Storage](#html-local-storage)
  - [HTML Session Storage](#html-session-storage)
- [HTML Forms (Advanced) (Continued)](#html-forms-advanced-continued)
  - [HTML Datalist](#html-datalist)
  - [HTML Meter](#html-meter)
  - [HTML Progress](#html-progress)

Feel free to ask for more information or specify particular topics you'd like to cover!

## HTML

HTML (Hypertext Markup Language) is a standard markup language for creating web documents (web pages). It is used to structure content on the web, defining elements and their relationships.

![html-tags-list](https://github.com/Mmustafa-772002/Html/assets/116543187/e1c0400f-c46f-48ab-ae46-aba74d9d0c1b)



## HTML Elements

An HTML element is composed of a start tag, some content, and an end tag. Elements may also have attributes that provide additional information.

```html
<tagname> attribute="value">Content goes here...</tagname>
```

## HTML Tags

HTML tags are the building blocks of HTML elements. They are surrounded by angle brackets and represent specific elements.

```html
<tagname>Content goes here...</tagname>
```

## The `<!DOCTYPE>` Declaration

The `<!DOCTYPE>` declaration represents the document type and ensures that browsers display web pages correctly. It is placed at the top of the HTML document.

```html
<!DOCTYPE html>
```

## HTML Page Structure

The basic structure of an HTML page includes the `<html>`, `<head>`, and `<body>` elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

## HTML Headings

HTML headings range from `<h1>` to `<h6>`, indicating different levels of importance.

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

## HTML Paragraphs

Paragraphs are defined with the `<p>` tag.

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

## HTML Links

Hyperlinks are created using the `<a>` tag.

```html
<a href="https://www.w3schools.com">This is a link</a>
```

## HTML Images

Images are displayed using the `<img>` tag. Attributes such as `src`, `alt`, `width`, and `height` are commonly used.

```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142" />
```

## HTML Buttons

Buttons are created with the `<button>` tag.

```html
<button>Click me</button>
```

## HTML Lists

Lists can be either unordered (`<ul>`) or ordered (`<ol>`), with list items specified by `<li>`.

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

## HTML Tables

Tables are defined with the `<table>` tag, containing rows (`<tr>`), headers (`<th>`), and data cells (`<td>`).

```html
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

## HTML Forms

Forms are created with the `<form>` tag, incorporating various input types for user interaction.

```html
<form>
  <label for="fname">First name:</label><br />
  <input type="text" id="fname" name="fname" /><br />
  <label for="lname">Last name:</label><br />
  <input type="text" id="lname" name="lname" />
</form>
```

## HTML Iframes

An iframe is used to embed another webpage within the current page.

```html
<iframe
  src="https://www.w3schools.com"
  title="W3Schools Free Online Web Tutorials"
></iframe>
```

## HTML Colors

Colors can be specified using predefined names or with RGB, HEX, HSL, RGBA, or HSLA values.

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<h1 style="background-color:Tomato;">Hello World</h1>
<h1 style="background-color:MediumSeaGreen;">Hello World</h1>
```

## HTML CSS

CSS (Cascading Style Sheets) is used to style HTML elements. Styles can be applied directly in the HTML file or in a separate CSS file.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        background-color: linen;
      }

      h1 {
        color: maroon;
        margin-left: 40px;
      }
    </style>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

## HTML JavaScript

JavaScript is the programming language of HTML and the Web. It enhances interactivity and dynamic behavior.

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>My First Web Page</h1>
    <p>My First Paragraph</p>

    <script>
      document.write("Hello World!");
    </script>
  </body>
</html>
```

## HTML File Paths

File paths describe the location of files in a website's folder structure, used for linking external files.

```html
<!DOCTYPE html>
<html>
  <body>
    <p><a href="/html/default.asp">HTML Tutorial</a></p>
    <p><a href="/css/default.asp">CSS Tutorial</a></p>
    <p><a href="/js/default.asp">JavaScript Tutorial</a></p>
  </body>
</html>
```

## HTML Head

The `<head>` element contains metadata and is placed between the `<html>` and `<body>` tags.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

## HTML Layout Elements

Semantic elements like `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<details>`, and `<summary>` define different parts of a web page.

```html
<header>
  <h1>Website Header</h1>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<section>
  <h2>Section Title</h2>
  <p>Section content goes here.</p>
</section>

<article>
  <h2>Article Title</h2>
  <p>Article content goes here.</p>
</article>

<aside>
  <h2>Aside Title</h2>
  <p>Aside content goes here.</p>
</aside>

<footer>
  <p>&copy; 2024 Website Name</p>
</footer>

<details>
  <summary>Additional Details</summary>
  <p>Details content goes here.</p>
</details>
```

## HTML Styles

The HTML `style` attribute adds styles to an element, controlling aspects like color, font, and size.

```html
<h1 style="color:blue;">This is a Blue Heading</h1>
<h1 style="color:red;">This is a Red Heading</h1>
```

## HTML Formatting

HTML provides various tags for text formatting, including `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, and `<sup>`.

```html
<b>Bold text</b>
<strong>Important text</strong>
<i>Italic text</i>
<em>Emphasized text</em>
<mark>Marked text</mark>
<small>Smaller text</small>
<del>Deleted text</del>
<ins>Inserted text</ins>
<sub>Subscript text</sub>
<sup>Superscript text</sup>
```

## HTML Quotations

Quotations are represented by the `<blockquote>` and `<q>` tags.

```html
<blockquote>
  <p>This is a blockquote.</p>
</blockquote>

<p>Here is a short inline <q>quotation</q>.</p>
```

## HTML Comments

HTML comments are not displayed in the browser but are useful for documentation.

```html
<!--This is a comment. Comments are not displayed in the browser-->
```

## HTML Classes

HTML classes are used to group HTML elements together. The HTML class attribute defines the class name for an element. The class name can be used by CSS and JavaScript to perform certain tasks for elements with the specified class name.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .city {
        background-color: tomato;
        color: white;
        border: 2px solid black;
        margin: 20px;
        padding: 20px;
      }
    </style>
  </head>
  <body>
    <h2 class="city">London</h2>
    <p>London is the capital of England.</p>

    <h2 class="city">Paris</h2>
    <p>Paris is the capital of France.</p>
  </body>
</html>
```

## HTML Id

The HTML id attribute is used to specify a unique id for an HTML element. The value must be unique within the HTML document. The id attribute is used by CSS or JavaScript to perform certain tasks for the element with the specific id value.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      #para1 {
        text-align: center;
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p id="para1">This is a paragraph.</p>
  </body>
</html>
```

## HTML Blocks

HTML block-level elements always start on a new line and take up the full width available. The `<div>` element is a block-level element.

```html
<div>This is a div element</div>
```

Certainly! Let's continue adding more content to cover additional aspects of HTML:

---

## HTML Multimedia

### HTML Audio

Embedding audio is done with the `<audio>` tag. You can use attributes like `controls` for playback options.

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
  Your browser does not support the audio tag.
</audio>
```

### HTML Video

Similarly, video content is added with the `<video>` tag. Specify the source and use attributes like `controls` for video playback.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
```

## HTML Embedding

### HTML Embed

Embedding external content like maps or multimedia can be achieved using the `<embed>` tag.

```html
<embed type="application/pdf" src="document.pdf" width="600" height="400" />
```

### HTML Object

The `<object>` tag provides another way to embed external content, and it allows fallback content.

```html
<object data="movie.mp4" width="400" height="300">
  <embed src="movie.mp4" width="400" height="300" />
</object>
```

## HTML Semantic Elements

### HTML Header & Footer

The `<header>` and `<footer>` elements define the header and footer of a document or section.

```html
<header>
  <h1>Document Title</h1>
</header>

<footer>
  <p>&copy; 2024 Your Company</p>
</footer>
```

### HTML Navigation & Section

Use the `<nav>` and `<section>` tags for navigation menus and sections of content.

```html
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section>
  <h2>About Us</h2>
  <p>Learn more about our company...</p>
</section>
```

### HTML Article & Aside

The `<article>` and `<aside>` tags define standalone content and content related to the surrounding text.

```html
<article>
  <h2>Article Title</h2>
  <p>Article content goes here.</p>
</article>

<aside>
  <h2>Related Links</h2>
  <ul>
    <li><a href="#link1">Link 1</a></li>
    <li><a href="#link2">Link 2</a></li>
  </ul>
</aside>
```

### HTML Details & Summary

Use the `<details>` and `<summary>` tags to create a disclosure widget for additional information.

```html
<details>
  <summary>More Details</summary>
  <p>Additional content goes here.</p>
</details>
```

## HTML Forms (Advanced)

### HTML Input Types

In addition to text inputs, HTML supports various input types like checkboxes, radio buttons, and date pickers.

```html
<form>
  <input type="text" name="username" placeholder="Username" /><br />
  <input type="password" name="password" placeholder="Password" /><br />
  <input type="checkbox" name="subscribe" value="subscribe" /> Subscribe<br />
  <input type="radio" name="gender" value="male" /> Male
  <input type="radio" name="gender" value="female" /> Female<br />
  <input type="date" name="birthdate" />
</form>
```

### HTML Form Validation

Use the `required` attribute for form fields and the `pattern` attribute for custom validation.

```html
<form>
  <input type="text" name="username" placeholder="Username" required /><br />
  <input
    type="password"
    name="password"
    placeholder="Password"
    required
    pattern=".{6,}"
  />
  <input type="submit" value="Submit" />
</form>
```

## HTML Metadata

### HTML Meta Tags

The `<meta>` tag provides metadata about the HTML document, such as character set and viewport settings.

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

### HTML Base

The `<base>` tag specifies a base URL/target for all relative URLs in a document.

```html
<base href="https://www.example.com/" /> <a href="page.html">Link to Page</a>
```

Certainly! Let's continue with more content, covering additional HTML concepts and features:

---

# HTML Report Generated by Pandoc (Continued)

## HTML Scripting

### HTML Script

JavaScript code can be included in HTML using the `<script>` tag, either within the document or by linking to an external script file.

```html
<script>
  alert("Hello, World!");
</script>

<script src="myscript.js"></script>
```

### HTML Noscript

The `<noscript>` tag is used to provide alternative content when scripts are not supported or disabled.

```html
<noscript>
  <p>JavaScript is disabled in your browser.</p>
</noscript>
```

## HTML Media Attributes

### HTML Audio Attributes

Additional attributes for the `<audio>` tag, like `autoplay` and `loop`, control audio playback.

```html
<audio controls autoplay loop>
  <source src="audio.mp3" type="audio/mp3" />
  Your browser does not support the audio tag.
</audio>
```

### HTML Video Attributes

Similarly, the `<video>` tag can have attributes such as `autoplay`, `controls`, and `loop` for video playback control.

```html
<video width="320" height="240" controls autoplay loop>
  <source src="movie.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
```

## HTML Responsive Design

### HTML Responsive Images

Make images responsive using the `max-width` style property.

```html
<img src="responsive.jpg" alt="Responsive Image" style="max-width:100%;" />
```

### HTML Responsive Tables

For tables, the `overflow-x` property ensures horizontal scrolling on small screens.

```html
<table style="width:100%; overflow-x:auto;">
  <!-- table content here -->
</table>
```

## HTML Accessibility

### HTML Aria Attributes

ARIA (Accessible Rich Internet Applications) attributes enhance accessibility for users with disabilities.

```html
<button aria-label="Close" onclick="closeDialog()">X</button>
```

### HTML Figure and Figcaption

Use the `<figure>` and `<figcaption>` tags to provide accessible captions for images.

```html
<figure>
  <img src="accessible.jpg" alt="Accessible Image" />
  <figcaption>Image description for accessibility.</figcaption>
</figure>
```

## HTML SVG

### HTML SVG Element

The `<svg>` element embeds scalable vector graphics directly in HTML.

```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
</svg>
```

## HTML Web Components

### HTML Custom Elements

Define and use custom HTML elements with the `<custom-element>` tag.

```html
<custom-element></custom-element>
```

### HTML Template Element

The `<template>` tag holds HTML that is not to be rendered when the page loads.

```html
<template id="myTemplate">
  <p>This content is a template.</p>
</template>
```

## HTML Storage

### HTML Local Storage

Use the `localStorage` object to store key-value pairs locally in the user's browser.

```html
<script>
  localStorage.setItem("username", "john_doe");
  let storedUsername = localStorage.getItem("username");
</script>
```

### HTML Session Storage

Similar to local storage but limited to a session. Data is cleared when the session ends.

```html
<script>
  sessionStorage.setItem("theme", "dark");
  let currentTheme = sessionStorage.getItem("theme");
</script>
```

## HTML Forms (Advanced)

### HTML Datalist

The `<datalist>` element provides a predefined list of options for input elements.

```html
<input list="browsers" name="browser" id="browser" />
<datalist id="browsers">
  <option value="Chrome"></option>
  <option value="Firefox"></option>
  <option value="Safari"></option>
  <option value="Edge"></option>
  <option value="Opera"></option>
</datalist>
```

### HTML Meter

The `<meter>` element represents a scalar measurement within a given range.

```html
<meter value="70" min="0" max="100">70%</meter>
```

### HTML Progress

The `<progress>` element represents the completion progress of a task.

```html
<progress value="50" max="100">50%</progress>
```

Certainly! Let's continue exploring more HTML concepts and features:

---

# HTML Report Generated by Pandoc (Continued)

## HTML Multimedia

### HTML Canvas

The `<canvas>` element provides a drawable region on the page, allowing for dynamic graphics and animations.

```html
<canvas
  id="myCanvas"
  width="200"
  height="100"
  style="border:1px solid #000;"
></canvas>
<script>
  var canvas = document.getElementById("myCanvas");
  var ctx = canvas.getContext("2d");
  ctx.fillStyle = "#FF0000";
  ctx.fillRect(10, 10, 50, 50);
</script>
```

### HTML Audio

The `<audio>` tag allows embedding audio files on a webpage.

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
  Your browser does not support the audio element.
</audio>
```

### HTML Video

Similarly, the `<video>` tag is used for embedding videos.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
```

## HTML Advanced Forms

### HTML Fieldset and Legend

Group related form elements using `<fieldset>` and add a description with `<legend>`.

```html
<form>
  <fieldset>
    <legend>Contact Information</legend>
    Name: <input type="text" /><br />
    Email: <input type="text" /><br />
  </fieldset>
</form>
```

### HTML Optgroup

The `<optgroup>` element groups related `<option>` elements within a `<select>` dropdown.

```html
<select>
  <optgroup label="Fruits">
    <option value="apple">Apple</option>
    <option value="orange">Orange</option>
  </optgroup>
  <optgroup label="Vegetables">
    <option value="carrot">Carrot</option>
    <option value="broccoli">Broccoli</option>
  </optgroup>
</select>
```

### HTML Output

The `<output>` element represents the result of a calculation or user action.

```html
<form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
  <input type="range" id="a" value="50" />+
  <input type="number" id="b" value="50" />
  =<output name="result" for="a b">100</output>
</form>
```

## HTML APIs and Integration

### HTML Geolocation API

The Geolocation API provides location information of the device.

```html
<button onclick="getLocation()">Get Location</button>
<script>
  function getLocation() {
    if (navigator.geolocation) {
      navigator.geolocation.getCurrentPosition(showPosition);
    } else {
      alert("Geolocation is not supported by this browser.");
    }
  }

  function showPosition(position) {
    alert(
      "Latitude: " +
        position.coords.latitude +
        "<br>Longitude: " +
        position.coords.longitude
    );
  }
</script>
```

### HTML Drag and Drop

The Drag and Drop API enables dragging elements across the page.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      #div1 {
        width: 350px;
        height: 70px;
        padding: 10px;
        border: 1px solid #aaaaaa;
      }
    </style>
    <script>
      function allowDrop(ev) {
        ev.preventDefault();
      }

      function drag(ev) {
        ev.dataTransfer.setData("text", ev.target.id);
      }

      function drop(ev) {
        ev.preventDefault();
        var data = ev.dataTransfer.getData("text");
        var draggedElement = document.getElementById(data);
        var clone = draggedElement.cloneNode(true);
        ev.target.appendChild(clone);
      }
    </script>
  </head>
  <body>
    <p>Drag the W3Schools image into the rectangle:</p>

    <div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>
    <br />
    <img
      id="drag1"
      src="w3schools.jpg"
      draggable="true"
      ondragstart="drag(event)"
      width="336"
      height="69"
    />
  </body>
</html>
```

### HTML WebSockets

WebSockets provide full-duplex communication channels over a single, long-lived connection.

```html
<script>
  var socket = new WebSocket("wss://echo.websocket.org");

  socket.onopen = function (event) {
    socket.send("Hello, WebSocket!");
  };

  socket.onmessage = function (event) {
    alert("Server says: " + event.data);
  };

  socket.onclose = function (event) {
    if (event.wasClean) {
      alert(
        "Connection closed cleanly, code=" +
          event.code +
          ", reason=" +
          event.reason
      );
    } else {
      alert("Connection died");
    }
  };

  socket.onerror = function (error) {
    alert("Error: " + error.message);
  };
</script>
```

END OF FILES
