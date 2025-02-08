<!-- @format -->

# The JavaScript Handbook: A Beginner's Guide to Understanding JavaScript

<div align="center">
    <img src="Images/Javascript-Logo.png" alt="Project Logo" width=30%>
</div>

## What is JavaScript?

- **JavaScript** is a **Client Side Scripting Language** used to create **Dynamic** & **Interactive** content on websites.
- It works alongside **HTML** & **CSS** to build modern web applications.
- **JavaScript** is **untested**, **multi-paradigm** & **event-driven** allowing developers to build interactive user interfaces.
- It is **interpreted** by the browser’s **JavaScript engine**, meaning it runs directly in the **browser** without compilation.

## JavaScript Features

- **Untyped** : Variables don't require a specific data type providing flexibility in usage.
- **Multi-paradigm** : Supports object-oriented, functional & imperative programming styles.
- **Functional** : Functions are first-class citizens, enabling higher-order functions & functional - programming techniques.
- **Event-driven** : JavaScript reacts to user interactions like clicks, keypresses & other events in real time.
- **Interpreted** : JavaScript is interpreted by the browser’s engine enabling immediate execution of the code in the client-side environment.

## JavaScript Advantages

- **Less Server Interactions** : **JavaScript** allows tasks to be done in the browser reducing the need to communicate with the server which speeds up web pages.
- **Better Performance** : It runs directly in the browser making the website faster & more responsive.
- **Richer Interface** : JavaScript helps create engaging & interactive web pages with animations & real-time updates.
- **Increased Interactivity** : JavaScript makes websites more interactive by responding to user actions like clicks & keystrokes creating a better user experience.

## 🌐 How a Website Works?

A website is a collection of web pages stored on a server. When a user enters a URL the browser requests files from the server, processes them & displays the webpage.

Here's a simplified workflow of how a website works:

1. User enters a URL in the browser.
2. Browser sends a request to the web server.
3. Server processes the request and sends back the necessary files (HTML, CSS, JavaScript).
4. Browser renders the website using these files.
5. User interacts with the website & JavaScript updates content dynamically.

> **Diagram of How a Website Works**

<div align="center">
    <img src="Images/Website-Workflow.png" width=80%>
</div>

### Explanation of the Workflow

- **User Request** → Enters a URL in the browser.
- **DNS Lookup** → Converts the domain name to an IP address.
- **Server Request** → Sends an HTTP request to the web server.
- **Server Response** → Sends back HTML, CSS & JavaScript files.
- **Rendering** → The browser processes and displays the webpage.
- **User Interaction** → JavaScript updates the page dynamically.

## 🖥 How a Browser Works with HTML, CSS & JavaScript?

A browser processes a webpage by handling three core technologies:

- **HTML** (**Structure**) → The browser parses HTML &and builds the DOM (Document Object Model) defining the webpage structure.
- **CSS** (**Style**) → The browser processes CSS to create the CSSOM (CSS Object Model) applying styles to elements.
- **JavaScript** (**Behavior**) → JavaScript manipulates the DOM & CSSOM making the webpage interactive and dynamic.
- **Rendering Process** →
  - The browser combines the DOM & CSSOM into a Render Tree.
  - It calculates layout, determining element positions.
  - The painting process renders the final visual output on the screen.
  - This ensures that webpages load, display & function properly.

**_Example_**: When you click a button JavaScript modifies the HTML (DOM) & updates styles (CSSOM) dynamically.

## 📌 HTML -HyperText Markup Language

### 🔹What is HTML?

HTML is the foundation of every website. It structures the webpage using elements like headings, paragraphs, links, images & forms.

### 🔹Key Features of HTML

- **Markup Language** → Uses tags to define elements.
- **Static Content** → Only provides structure no interactivity.
- **Hierarchy-Based** → Uses a tree-like structure (DOM).
- **Semantic Elements** → Tags describe meaning (e.g., <header>, <article>).
- **Compatible with CSS & JavaScript** → Works together to style & add functionality.

### Basic Structure of an HTML Document

```html
    <!DOCTYPE html> <!-- Defines document type -->
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My First Webpage</title> <!-- Page title in the browser tab -->
    </head>
    <body>
        <h1>Hello, World!</h1> <!-- Main heading -->
        <p>This is a paragraph.</p> <!-- Paragraph text -->
    </body>
    </html>
```

> **Breakdown**

- **`<html>`** → Root element of the webpage.
- **`<head>`** → Contains metadata like title, character set & CSS links.
- **`<body>`** → Contains visible content (text, images, buttons).

### Common HTML Tags

<div align="center">

| **Element**                         | **Description**                          |
| ----------------------------------- | ---------------------------------------- |
| `<h1>` - `<h6>`                     | Headings (h1 = largest, h6 = smallest)   |
| `<p>`                               | Paragraphs                               |
| `<a href="">`                       | Hyperlinks                               |
| `<img src="">`                      | Images                                   |
| `<ul>`, `<ol>`                      | Unordered & Ordered lists                |
| `<table>`                           | Tables                                   |
| `<form>`                            | Forms (used for user input)              |
| `<input>`                           | Input fields                             |
| `<button>`                          | Buttons                                  |
| `<div>`, `<span>`                   | Grouping & inline elements               |
| `<header>`, `<footer>`, `<section>` | Semantic elements for better readability |
| `<b>`                               | Bold text                                |
| `<strong>`                          | Important text (strong emphasis)         |
| `<i>`                               | Italic text                              |
| `<em>`                              | Emphasized text                          |
| `<u>`                               | Underlined text                          |
| `<mark>`                            | Marked text                              |
| `<small>`                           | Smaller text                             |
| `<del>`                             | Deleted text                             |
| `<ins>`                             | Inserted text                            |
| `<sub>`                             | Subscript text                           |
| `<sup>`                             | Superscript text                         |
| `<br>`                              | Line break                               |
| `<hr>`                              | Horizontal rule                          |
| `<tr>`                              | Table row                                |
| `<th>`                              | Table header cell                        |
| `<td>`                              | Table data cell                          |
| `<textarea>`                        | Multiline text input                     |
| `<select>`                          | Dropdown list                            |
| `<option>`                          | Option within a dropdown list            |
| `<tr>`                              | Table row                                |
| `<th>`                              | Table header cell                        |
| `<td>`                              | Table data cell                          |
| `<ul>`                              | Unordered list                           |
| `<ol>`                              | Ordered list                             |
| `<li>`                              | List item                                |
| `<header>`                          | Page header                              |
| `<footer>`                          | Page footer                              |
| `<nav>`                             | Navigation links                         |
| `<article>`                         | Self-contained content                   |
| `<aside>`                           | Sidebar content                          |
| `<main>`                            | Main content of a document               |

</div>

## 🎨 CSS (Cascading Style Sheets) - Detailed Explanation

### 🔹What is CSS?

CSS styles HTML elements, making the webpage visually appealing. It controls layout, colors, fonts, spacing, animations & responsiveness.

### 🔹Key Features of CSS

- **Separation of Concerns** → HTML for structure CSS for style.
- **Selectors & Rules** → Defines styles using selectors & rules.
- **Box Model** → Controls spacing (margin, padding, border).
- **Responsive Design** → Adjusts layout for different screen sizes.
- **Animations & Effects** → Enhances user experience.

### 🔹Ways to Add CSS

<div align="center">

| **Method**   | **Description**                                   |
| ------------ | ------------------------------------------------- |
| Inline CSS   | Inside an HTML tag using the `style` attribute.   |
| Internal CSS | Inside a `<style>` tag within `<head>`.           |
| External CSS | In a separate `.css` file, linked using `<link>`. |

</div>

### 🔹CSS Selectors

CSS **Targets Elements** using **Selectors**.

<div align="center">

| **Selector**          | **Example**                     | **Description**                        |
| --------------------- | ------------------------------- | -------------------------------------- |
| Element               | `p { color: red; }`             | Styles all `<p>` elements              |
| Class (.)             | `.button { background: blue; }` | Targets elements with class="button"   |
| ID (#)                | `#header { font-size: 20px; }`  | Targets element with id="header"       |
| Group (A, B)          | `h1, p { color: black; }`       | Styles multiple elements at once       |
| Child (>)             | `div > p { color: green; }`     | Targets `<p>` inside a `<div>`         |
| Descendant ()         | `div p { color: red; }`         | Styles `<p>` inside `div` at any level |
| Pseudo-class (:hover) | `a:hover { color: red; }`       | Styles element on a specific state     |

</div>

## ✅ Summary

### 📌HTML

- Defines structure using elements like headings, paragraphs, lists, images.
- Forms allow user input (e.g., login, contact forms).
- Semantic HTML improves SEO & accessibility.

### 📌CSS

- Styles HTML by adding colors, spacing & layouts.
- Selectors help target elements precisely.
- Box Model controls spacing (margin, padding, border).
- Flexbox & Grid help create modern layouts.
- Media Queries make the website mobile-friendly.
