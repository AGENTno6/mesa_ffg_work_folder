# HTML Basics

## The Basics

- HTML elements are created with tags: `<openingTag>content to be shown</closingTag>`.
- The elements job is to structure and define the page.
- The **HTML Tag** is the element name surrounded by opening '<' and closing '>' angle brackets.
- Some HTML elements have self closing tags like the image tag: `<img />`.
- HTML elements have **attributes** that add necessary information about the element.
  - **Attributes have 2 components, the *name of the attribute* and the *value of the attribute* element**.
  - **Ie:** The `src` attribute used in an image element, `<img />`, tells the browser which image to display.
  - **Ie:** The `href` attribute tells the browser where to direct users who click on the link. `<a href="insert url here">Click this link!</a>`
  - Other attributes like the `id` and `class` attributes do come in handy to add additional information but we wont worry about them just yet.

```
<div class='container'>
   <h1>This is a heading wrapped in 'h1' tags.</h1>
   <p>This is some text.</p>
   <img alt="a picture of a cat" src="some-animal-photo.jpg">
   <a href="https://www.mesacharter.org/">Click here to visit the MESA Charter HS website.</a>
   <p id="last-paragraph">This is some fluff.</p>
</div>
```

## HTML Structure

HTML is structured as a collection of family tree relationships. The element inside another element is considered the child of that parent element.

### The Body

**Only content within the opening and closing <body> tags can be (rendered)displayed to the screen.**

```
<body>
  <p>This text is the child of the body.</p>
</body>
```

### Divs
`<div>` is short for **division**; also known as a container that divides the page into sections. 
<br> `<div>`'s can contain any type of content.

### Text
HTML can be used to style text.
<br> The `<em>` tag will render as *italic* emphasis.
The `<strong>` tag will render as **BOLD** emphasis.

### Un-ordered Lists
The un-ordered list tag, `<ul>`
- is used to create a list of items in **NO ORDER**.
- outlines individual items with a bullet point.

The `<ul>` element shouldn't hold raw text and wont *automatically* format raw text into an un-ordered list of items.
Individual items must be added to the list using the list tag, `<li></li>`.

Example:
```
<ul>
  <li>Limes</li>
  <li>Tortillas</li>
  <li>Chicken</li>
</ul>
```

### Ordered Lists
Ordered lists, `<ol></ol>`, list each item numbered.
- useful for writing different steps or ranking first to last.
Individual list items are written as, `<li>Crack eggs</li>`.
----------------

### Understanding your elements.⚗️

![image](https://github.com/AGENTno6/mesa_ffg_work_folder/assets/114108199/0bf266fe-71ea-426a-9f55-9a5e92a21923)

Above is a diagram of how an HTML element is structured. You use attributes like the _style_ attribute by giving it a **value** in order to manipulate the style of the element.

---

## Here are some common HTML elements used:

`<p></p>` -> **the paragraph tag** -> this element is used for adding general **text** to your webpage.<br>
`<div></div>` -> **the div tag** -> this element is used to define a division or section.
<br> Headings come in various font size specified with tags `<h1>`, having the largest font-size, through `<h6>`, having the smallest font-size of the headings.
<br> `<img />` -> **the image tag** -> this element is used to link an image to your webpage. In order to link

---

## Everything is a Box!!

**Things to know:**

- HTML and CSS are languages just like JavaScript.
  - Lets look back at our toolbags to remember what each language allows us to do:
    image.png

I know it sounds quirky but the best way to think when it comes to HTML is with the idea that **everything is a box**.

---
