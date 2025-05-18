# HTML Tutorial

Welcome to the complete HTML tutorial! This guide is designed for beginners and intermediate users to learn and understand HTML (HyperText Markup Language), the foundation of web development.

---

## Table of Contents

1. [Introduction to HTML](#introduction-to-html)
2. [Basic Structure](#basic-structure)
3. [Text Formatting](#text-formatting)
4. [Links](#links)
5. [Images](#images)
6. [Lists](#lists)
7. [Tables](#tables)
8. [Forms](#forms)
9. [Semantic Elements](#semantic-elements)
10. [Multimedia](#multimedia)
11. [HTML5 New Features](#html5-new-features)
12. [Best Practices](#best-practices)

---

## Introduction to HTML

HTML stands for HyperText Markup Language. It is used to create web pages and web applications. HTML describes the structure of a web page using markup.

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Page</title>
</head>
<body>
  <h1>Hello, world!</h1>
</body>
</html>
```

---

## Basic Structure

Every HTML document has the following structure:

* `<!DOCTYPE html>`: Defines the document type
* `<html>`: Root element
* `<head>`: Contains metadata
* `<body>`: Contains the content of the document

---

## Text Formatting

HTML provides tags for formatting text:

* `<h1>` to `<h6>`: Headings
* `<p>`: Paragraph
* `<b>` / `<strong>`: Bold text
* `<i>` / `<em>`: Italic text
* `<u>`: Underline
* `<br>`: Line break
* `<hr>`: Horizontal line

Example:

```html
<h1>Main Heading</h1>
<p>This is a <strong>bold</strong> and <em>italic</em> text.</p>
```

---

## Links

Use the `<a>` tag to create hyperlinks:

```html
<a href="https://example.com">Visit Example</a>
```

Attributes:

* `href`: URL of the link
* `target="_blank"`: Open in a new tab

---

## Images

The `<img>` tag is used to embed images:

```html
<img src="image.jpg" alt="Description" width="300">
```

Attributes:

* `src`: Path to the image
* `alt`: Alternative text
* `width`, `height`: Image size

---

## Lists

### Ordered List:

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```

### Unordered List:

```html
<ul>
  <li>Item A</li>
  <li>Item B</li>
</ul>
```

---

## Tables

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
  </tr>
</table>
```

---

## Forms

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>
```

Common input types:

* `text`, `password`, `checkbox`, `radio`, `submit`, `email`

---

## Semantic Elements

Semantic HTML gives meaning to web content:

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<footer>`

---

## Multimedia

### Audio:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

### Video:

```html
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

---

## HTML5 New Features

* `<canvas>`: For graphics and games
* `<video>` and `<audio>`: Native multimedia support
* `<section>`, `<article>`, `<nav>`, `<aside>`: Semantic structure
* Form enhancements: `date`, `range`, `color`, etc.

---

## Best Practices

* Always use semantic tags
* Keep the code clean and readable
* Use lowercase for tag names and attributes
* Use the `alt` attribute for images
* Validate HTML using [W3C Validator](https://validator.w3.org/)

---

Happy coding!

