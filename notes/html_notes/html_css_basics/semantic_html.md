# Semantic HTML

Lets start off basic, what does _semantic_ mean?

_Semantic_ simply means, related to meaning.<br>
In our case, semantic elements provide info about the content between the opening and closing tags.<br>

![1691429662154](https://github.com/AGENTno6/mesa_ffg_work_folder/assets/114108199/3e4974c1-993d-48f7-a08b-17c57659ea58)

### Benefits of using semantic HTML

- Accessibility
- Semantic HTML makes a site more accessible for mobile devices and disable users because **screen readers and browsers are able to read semantic HTML much better**.

---

#### Search Engine Optimization (SEO)

The process of increasing site traffic.<br>
With better SEO, search engines are better able to identify the content of a site.

---

## Semantic HTML Elements

`<header>` - a container usually for either navigational links or introductory content containing `<h1>` to `<h6>` headings.<br>
`<nav>` - used to define a block of navigational links like menus and tables of content.<br> **nav can be used independently or within the `<header>` tags**

### Main && Footer

`<main>` - used to encapsulate the dominant content within webpage.<br>
`<footer>` - used to encapsulate the content at the bottom of the webpage. The footer may contain:

- Contact info
- Copyright info
- Terms of use
- Site map
- Reference to top of page links

### Article && Section

`<article>` - holds content that makes sense on its own.

- articles, blogs comments, magazines etc.
  <br> An article would help an impaired user using the screen reader to understand where article content begins and ends.<br>

`<section>` - defines elements in a document such as chapters, headings or any other area of the document with the same theme.

- Ie. Content with the same theme like articles about football, can be within one <section>.

### Aside Element

`<aside>` - used to print additional information that can enhance another element but isnt required in order to understand the main content.<br>
**Common uses:**

- bibliographies
- endnotes
- comments
- pull quotes
- editorial sidebars
- additional information

### Audio && Attributes

`<audio>` - used to embed audio content into a document.<br>
**its best to specify the type of audio it is (refer to acceptable attribute values)**<br>

**Audio Attributes**<br>
`src`- specifies the URL of the audio file.<br>
`type` - specifies the type of file.<br>
`controls`- automatically displays the audio controls into the browser such as play and mute.

### Video

`<video>`- this element makes it clear that a developer is attempting to display a video to the user.<br>
Some attributes that can alter a video playback:

- src - specifies the URL of the video.
- controls- automatically displays the video controls into the browser such as play and pause or fullscreen.
- autoplay- results in veo automatically playing as soon as the page is loaded.
- loop- results in the video continuously playing on repeat.
