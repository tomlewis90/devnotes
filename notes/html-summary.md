# HTML 

## 1. HTML
- HTML stands for HyperText Markup Language
- It's the standard markup language for creating web pages
- HTML describes the structure of a web page semantically

## 2. Basic Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

## 3. Elements and Tags
- Elements are defined by tags
- Most elements have an opening and closing tag
- Example: `<p>This is a paragraph.</p>`

## 4. Attributes
- Provide additional information about elements
- Placed within the opening tag
- Example: `<a href="https://www.example.com">Link</a>`

## 5. Headings
- Six levels of headings: `<h1>` to `<h6>`
- `<h1>` is the highest (most important) level

## 6. Paragraphs
- Defined with the `<p>` tag
- Browsers automatically add space before and after each `<p>` element

## 7. Links
- Created with the `<a>` tag
- The `href` attribute specifies the URL
- Example: `<a href="https://www.example.com">Visit Example.com</a>`

## 8. Images
- Inserted with the `<img>` tag
- Requires `src` and `alt` attributes
- Example: `<img src="image.jpg" alt="Description of image">`

## 9. Lists
- Unordered lists: `<ul>` with `<li>` items
- Ordered lists: `<ol>` with `<li>` items
- Definition lists: `<dl>` with `<dt>` (term) and `<dd>` (description)

## 10. Tables
- Created with `<table>`
- Rows: `<tr>`
- Headers: `<th>`
- Data cells: `<td>`

## 11. Forms
- Created with the `<form>` element
- Various input types: text, password, radio, checkbox, etc.
- Submit button to send form data

## 12. Div and Span
- `<div>`: block-level container for grouping elements
- `<span>`: inline container for text

## 13. Semantic Elements
- Provide meaning to the structure: `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`

## 14. Comments
- Not displayed in the browser
- Useful for documentation
- Syntax: `<!-- This is a comment -->`

## 15. Meta Tags
- Provide metadata about the HTML document
- Placed within the `<head>` element
- Examples: charset, viewport, description

## 16. Multimedia
- Audio: `<audio src="sound.mp3" controls></audio>`
- Video: `<video src="movie.mp4" controls></video>`

## 17. Iframes
- Embed another document within the current HTML document
- Example: `<iframe src="https://www.example.com"></iframe>`

## 18. Special Characters
- Used to display reserved characters in HTML
- Example: `&lt;` for <, `&gt;` for >, `&amp;` for &