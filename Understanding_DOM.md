<!-- @format -->

<div align="center">

# DOM Explained with JavaScript

</div>

# What is DOM?

**DOM** stands for **Document Object Model**. It’s a **tree-like structure** created by the browser from the HTML document. Each HTML element becomes a node in the tree. JavaScript can use the DOM to access, change, add or remove elements on a webpage.

# Why DOM is Important

It allows dynamic interaction with the webpage. We can:

- Change content (**`innerText`**, **`innerHTML`**)
- Change styles (**`style.color`**, **`style.backgroundColor`**)
- Respond to events (**`click`**, **`submit`**, etc.)
- Create or delete HTML elements

# Example of DOM Tree

<div align="center">
    <img src="Images/DOM-Tree.png" alt="Project Logo" width=80%>
</div>

Here’s the **DOM tree structure** based on the HTML code from above image

<div align="center">
    <img src="Images/DOM-Tree01.png" alt="Project Logo" width=60%>
</div>

## Explanation

### 🌐 Top Level : Window

- Represents the browser window. It's the global object for everything in the browser.
- Everything—DOM, console, location, etc.—is accessed through the window.
