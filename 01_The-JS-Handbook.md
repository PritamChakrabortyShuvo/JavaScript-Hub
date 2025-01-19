<!-- @format -->

# The JavaScript Handbook: A Beginner's Guide to Understanding JavaScript

<div align="center">
    <img src="Images/Javascript-Logo.png" alt="Project Logo" width=30%>
</div>

## What is JavaScript?

- JavaScript is a client-side scripting language used to create dynamic & interactive content on websites.
- It works alongside HTML & CSS to build modern web applications.
- JavaScript is untested, multi-paradigm & event-driven, allowing developers to build interactive user interfaces.
- It is interpreted by the browser’s JavaScript engine, meaning it runs directly in the browser without compilation.

## JavaScript Features

- **Untyped** : Variables don't require a specific data type providing flexibility in usage.
- **Multi-paradigm** : Supports object-oriented, functional & imperative programming styles.
- **Functional** : Functions are first-class citizens, enabling higher-order functions & functional - programming techniques.
- **Event-driven** : JavaScript reacts to user interactions like clicks, keypresses & other events in real time.
- **Interpreted** : JavaScript is interpreted by the browser’s engine enabling immediate execution of the code in the client-side environment.

## JavaScript Advantages

- **Less Server Interactions** : JavaScript allows tasks to be done in the browser reducing the need to communicate with the server which speeds up web pages.
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

### 🔹 What is HTML?

HTML is the foundation of every website. It structures the webpage using elements like headings, paragraphs, links, images &forms.
