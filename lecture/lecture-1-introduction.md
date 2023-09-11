---
marp: true
---

# Introduction to HTML

---

# HTML or How To Make Lasagna

\*actually it's HyperText Markup Language

---

HTML is a fairly simple markup (not programming) language.

HTML is composed of `elements`.

`elements` provide both structure and content to webpages.

---

## Anatomy of an HTML `element`

<img src={anatomy} />

<br/>

Different tags are used to define different types of content and their layout on the webpage.

---

## Anatomy of an HTML element

<img src={attribute} />

| Property              | What is it                   |
| --------------------- | ---------------------------- |
| `<p>`                 | HTML element (tag)           |
| class                 | HTML attribute               |
| editor-note           | Value of the class attribute |
| My cat is very grumpy | Content of `<p>` tag         |

---

## Basic HTML template

HTML files are recognized by the file extension `.html`

This is what a basic HTML template looks like.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>A Basic HTML Template</title>
  </head>

  <body>
    <!-- all content here -->
  </body>
</html>
```

---

## Choose the right tag for the job

- Tags should be chosen based on the semantic value of the content
- Tags should **NEVER** ever be chosen based on presentation, or look.

This means that these tags are basically off limits:

`<big>` `<small>` `<i>` `<b>` `<center>` `<font>` `<hr/>` `<br/>`

---

## Choose the right tag for the job

Anytime you catch yourself thinking

"I should use `<tag>` because I need it to look like..."

# ✋ Stop! ✋

---

## Google ♥ Semantic HTML

Semantic HTML pleases Google. It is easier for it to crawl and index your site. This means

- A better ranking in search results.
- Less of a need to “game” the Google algorithm with SEO shenanigans.

---

## Semantic HTML = Accessibility

<a href="http://blogs.actuate.com/wp-content/uploads/2015/04/visualimpairmentstats.png" target="_blank" ><img src={stats} /></a>

- 22% of Canadians over the age of 15 live with at least one disability (6.2 million).
- 26% of Americans have some type of disability. (61 million).

---

## Semantic HTML = Accessibility

Policies and laws worldwide exist and will become more and more important in the future.

https://www.w3.org/WAI/policies/

### Fines of up to $250,000 😬

---

## Semantic HTML = Accessibility

### 🙏🏿 Always write good HTML 🙏🏻

---

## Elements

Different elements have different uses and meaning

We'll divide them into 4 groups:

1. Structural
2. Text
3. Media
4. Form

---

## 1. Structural Elements

Structural elements are generally containers of other elements

- `<html>`: the root element that encloses the entire web page
- `<head>`: contains metadata about the document
- `<body>`: the main content
- `<section>`: container for content grouped by a theme, ex: a chapter
- `<div>`: a generic container for grouping and styling content
- `<header>`: introductory content / site logo
- `<footer>`: usually contains information about the author, copyright, or contact details.
- `<nav>`: navigation menu
- `<article>`: self-contained content (ex: a blog post)
- `<aside>`: information about nearby content

---

## 2. Text Elements

contain text 😊

- `<p>`: a paragraph
- `<h1>` to `<h6>`: Headings of different levels
- `<span>`: A middle of text container
- `<a>`: hyperlinks to other web pages
- `<ul>` and `<ol>`: unordered / ordered lists
- `<li>`: list items within `<ul>` or `<ol>`

---

## 3. Media Elements

- `<img>`: images
- `<audio>`: audio
- `<video>`: video
- `<picture>`: device/resoltion dependant images

---

## 4. Form Elements

A form is generally a place where users input information

ex: a sign-up form

- `<form>`: form container
- `<input>`: checkboxes, text, dates, etc
- `<textarea>`: multi-line text input area
- `<button>`: clickable element
- `<select>`: dropdown list of options
- `<label>`: labels form elements for improved accessibility

---

## Structure

HTML elements will behave in one of two ways

1. They will stack on top of each other (block-level)

2. They will line up in a row (inline-level)

---

## 1. Block-level elements

`<h1>` `<h2>` `<h3>` `<h4>` `<h5>` `<h6>`

`<p>` `<ul>` `<ol>` `<li>`

`<table>` `<form>` `<div>`

---

## 2. Inline-level elements

`<img>` `<a>` `<span>` `<button>`

`<input>` `<label>` `<select>` `<option>`

`<textarea>`

---

## Choose the right tag for the job

What a semantic HTML site looks like:

<img src={semantic} />
