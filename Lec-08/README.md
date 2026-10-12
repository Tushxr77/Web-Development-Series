# Lecture 08 — Inline and Block Elements

## 📚 Overview

In this lecture, I learned about **block-level elements** and **inline elements** in HTML, and how they behave on a webpage.

I created a simple HTML page to practice how CSS styles can be applied to paragraph elements and hyperlinks.

## 🎯 Topics Learned

### 1. Block-Level Elements

Block-level elements generally start on a new line and occupy the available width of their containing block by default.

Common examples:

- `<div>` — Generic container
- `<p>` — Paragraph
- `<h1>` to `<h6>` — Headings
- `<ul>` and `<ol>` — Unordered and ordered lists
- `<li>` — List item
- `<form>` — Form container
- `<table>` — Table
- `<header>` — Introductory content
- `<footer>` — Footer content
- `<nav>` — Navigation links
- `<section>` — Thematic section
- `<article>` — Self-contained content
- `<main>` — Main page content
- `<blockquote>` — Block quotation
- `<pre>` — Preformatted text
- `<hr>` — Thematic break

### 2. Inline Elements

Inline elements generally flow within the surrounding text and occupy only the space they need.

Common examples:

- `<a>` — Hyperlink
- `<img>` — Image
- `<span>` — Generic inline container
- `<input>` — Form input
- `<label>` — Form label
- `<strong>` — Strong importance
- `<em>` — Emphasis
- `<br>` — Line break
- `<code>` — Code snippet
- `<b>` — Bold text
- `<i>` — Italic text
- `<u>` — Underlined text
- `<small>` — Smaller text
- `<sub>` and `<sup>` — Subscript and superscript
- `<mark>` — Highlighted text
- `<q>` — Short quotation
- `<time>` — Date or time

**Note:** An element's default display behavior can be changed using CSS. Some elements, such as `<li>`, have their own default display behavior, and modern HTML also includes elements whose behavior depends on context.

## 💻 Practice

I created a basic HTML page containing:

- A paragraph using the `<p>` tag
- A hyperlink using the `<a>` tag
- External CSS using the `<link>` tag
- CSS background colors for paragraph and anchor elements

### CSS Practice

```css
p {
    background-color: red;
}

a {
    background-color: blue;
}
```

This helped me understand how different HTML elements can be styled independently using CSS selectors.

## 🛠️ Technologies Used

- HTML5
- CSS3

## 📂 Folder Structure

```text
Lec-08/
├── README.md
└── Content/
    ├── index.html
    └── style.css
```

## 🧠 Key Learnings

- Block elements generally begin on a new line.
- Inline elements generally remain within the current line of text.
- HTML defines the structure and meaning of content.
- CSS controls the presentation and appearance of elements.
- The `<a>` tag creates hyperlinks using the `href` attribute.
- CSS selectors such as `p` and `a` target elements for styling.

## 📈 Learning Approach

**Learn → Understand → Practice → Build → Commit → Revise**

## ✅ Status

Completed — practiced the basic differences between inline and block elements.

## 📌 Note

This is a learning exercise created while studying Web Development. I will continue exploring HTML elements and CSS display properties as I progress.
