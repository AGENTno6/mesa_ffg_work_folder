# HTML Basics

## The Basics

- HTML elements are created with tags: `<openingTag>content to be shown</closingTag>`.
- The elements job is to structure and define the page.
- The **HTML Tag** is the element name surrounded by opening '<' and closing '>' angle brackets.
- Some HTML elements have self closing tags like the image tag: `<img />`.
- HTML elements have **attributes** that add necessary information about the element.
  - **Attributes have 2 components, the _name of the attribute_ and the _value of the attribute_ element**.
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

### Attributes

**Attributes**- content added to the openeing tag of an element && could be used for many things lke **providing info** to _changing styling_.

### Headings

There are 6 different heading elements:

```
<h1> Biggest font size </h1>
<h2>
<h3>
<h4>
<h5>
<h6>Smallest font size </h6>
```

### Text

Paragraphs (`<p>`) contain a block of plain text.
`<span>`'s contain short pieces of text or other HTML. Theyre used to separate small pieces of content that're on the same line as other content.

**For dividing content into blocks, use `<div>`'s.**

HTML can be used to style text.
<br> The `<em>` tag will render as _italic_ emphasis.
The `<strong>` tag will render as **BOLD** emphasis.

Styling can take place inline:

```
<div style="width:400px; background-color:'green';">
  <div style="width:200px;">
    <h3>One small div</h3>
  </div>
    <div style="width:200px; background-color:'blue';">
    <h3>Another small div</h3>
  </div>
</div>

And via your linked CSS Stylesheet.
```

### Line Breaks

Spacing between code does **NOT** affect the positioning of elements when they're rendered. (You must manually place and position everything.)

`<br>` - the line break element.
Only composed of an opening tag.

### Un-ordered Lists

The un-ordered list tag, `<ul>`

- is used to create a list of items in **NO ORDER**.
- outlines individual items with a bullet point.

The `<ul>` element shouldn't hold raw text and wont _automatically_ format raw text into an un-ordered list of items.
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

### Images

`<img>` tag allows you to link an image to a webpage.<br>
**self closing tag**

`<img src='image_name.png'/>`

<br> The image tag has a required attribute called `src`.
<br> The `src ` attribute **MUST** be set to the images source, or location of the image.

<a></a> defines a hyperlink, which is used to link something from one page to another. The most important attribute is `href` because it is used to specify the link destination.

### Image Alts

`alt` attribute = alternate text - the value should be a description of the image.
**can be added to the image tag like the src attribute**

#### Purposes of The alt Attribute

- If the site fails to show an image; you can hover over theintended spot and read the description provided through the `alt` attribute.
- When the visually impaired browse the web, they use a screen reader. Descriptions coded can be read aloud to your visually impaired users **IF** one uses the `alt` attribute.
- Utilizing the `alt` attribute plays a role in _Search Engine Optimization (SEO)_ by improving a sites ranking because search engines cant "see" the images, so the description is helpful to it.

### Videos

The `<video>` element requires a `src` attribute and a opening and closing tag.
**Ie:** <br>

```
<video src="my_video.mp4" width:'320' height:'260' controls > Video Not Supported.</video>
```

The width and height attributes are used to set the size of the vido displayed in the browser.<br>
The **controls** attribute tells the browser to include basic video controls with the video, like pausing and playing.

The text "Video Not Supported." between the opening and closing tags will **ONLY** be displayed if the browser is unable to load the video.

---

## Understanding your elements.⚗️

![image](https://github.com/AGENTno6/mesa_ffg_work_folder/assets/114108199/0bf266fe-71ea-426a-9f55-9a5e92a21923)

Above is a diagram of how an HTML element is structured. You use attributes like the _style_ attribute by giving it a **value** in order to manipulate the style of the element.
