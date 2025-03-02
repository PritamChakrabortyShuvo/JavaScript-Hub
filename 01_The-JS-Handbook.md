 <!-- @format -->

# The JavaScript Handbook: A Beginner's Guide to Understanding JavaScript

<div align="center">
    <img src="Images/Javascript-Logo.png" alt="Project Logo" width=30%>
</div>

## What is JavaScript?

- **JavaScript** is a **Client Side Scripting Language** used to create **Dynamic** & **Interactive** content on websites.
- It works alongside **HTML** & **CSS** to build modern web applications.
- **JavaScript** is **Untested**, **Multi-Paradigm** & **Event-Driven** allowing developers to **build interactive user interfaces**.
- It is **Interpreted** by the browser’s **JavaScript Engine**, meaning it runs directly in the **browser** without **compilation**.

## JavaScript Features

- **Untyped** : Variables don't require a specific data type providing **flexibility** in usage.
- **Multi-Paradigm** : Supports **object-oriented**, functional & imperative programming styles.
- **Functional** : Functions are first-class citizens, enabling higher-order functions & functional - programming techniques.
- **Event-driven** : JavaScript reacts to user interactions like clicks, keypresses & other events in real time.
- **Interpreted** : **JavaScript** is interpreted by the browser’s engine enabling immediate execution of the code in the client-side environment.

## JavaScript Advantages

- **Less Server Interactions** : **JavaScript** allows tasks to be done in the browser **reducing** the need to communicate with the server which speeds up web pages.
- **Better Performance** : It runs directly in the browser making the **website faster** & **more responsive**.
- **Richer Interface** : **JavaScript** helps create engaging & interactive web pages with animations & real-time updates.
- **Increased Interactivity** : **JavaScript** makes websites more **interactive** by responding to user actions like clicks & keystrokes creating a better user experience.

## 🌐 How a Website Works?

A **website** is a **collection of web pages** stored on a server. When a user enters a **URL** the browser requests files from the server processes them & displays the webpage.

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

## 🛠Installation Process of VS Code

### Step 1: Download VS Code

- Visit [VS Code Official Website](https://code.visualstudio.com/)
- Download the version for your OS (Windows, macOS, or Linux).

### Step 2: Install VS Code

- Open the downloaded file and follow the installation steps.
- Select Add to PATH (Recommended).
- Click Finish to complete the setup.

### Step 3: Open VS Code

- Launch VS Code and set up extensions if needed.

## 🛠 Installation Process of JavaScript

### Step 1: Download Node.js

- Visit [Node.js Official Website](https://nodejs.org/en)
- Download the **LTS Version** (Recommended).

### Step 2: Install **Node.js**

- Open the installer and follow the setup steps.
- Check **Add** to **PATH** (so you can use Node.js from the terminal).

### Step 3: Verify Installation

- Open the terminal and run:

```javascript
    node -v  # Check Node.js version
    npm -v   # Check npm (Node Package Manager) version
```

Now you can run **JavaScript** in **VS Code** using **Node.js**

## 🖥️ Running JavaScript in a Browser

In JavaScript, we can write and execute code inside an HTML file or in a separate JavaScript file.

### 🔹 Method 1: Internal JavaScript (Inside HTML)

We can write JavaScript directly inside the **`<script>`** tag in an **HTML** file.

> **Steps**

- Create an **`index.html`** file.
- Add JavaScript inside the **`<script>`** tag.
- Open the HTML file in a browser.

> **Example**

```javascript
    <!DOCTYPE html>
    <html>
    <head>
        <title>Internal JavaScript</title>
    </head>
    <body>
        <h1>Hello, World!</h1>
        <script>
            console.log("Hello, World! from Internal JavaScript");
        </script>
    </body>
    </html>
```

> **Output**

**Console Message** : "**`Hello, World! from Internal JavaScript`**" (View in **Console Tab**).

### 🔹 Method 2: External JavaScript (Separate File)

We can store JavaScript in a separate **`.js`** file & link it to the HTML file.

> **Steps**

- Create an **`index.html`** file.
- Create a **`script.js`** file in the same folder.
- Link the **`script.js`** file inside **`<script src="script.js"></script>`**
- Open **`index.html`** in a **browser**.

> **Example**

**📄 index.html** (Linking External JS File)

```javascript

    <!DOCTYPE html>
    <html>
    <head>
        <title>External JavaScript</title>
    </head>
    <body>
        <h1>Hello, World!</h1>

        <!-- Link External JavaScript File -->
        <script src="script.js"></script>
    </body>
    </html>
```

**📄 script.js** (External JavaScript Code)

```javascript
    console.log("Hello, World! from script.js");
```

> **✅ Output**

Console Message: "**`Hello, World! from script.js`**"

### 🎯Conclusion

- Use **Internal JavaScript** for \*small scripts\*\*.
- Use External JavaScript for clean, maintainable code.

## 📌Variables in JavaScript

A variable is a container used to store data that can be referenced and manipulated in a program.

### 🔹Key Concepts

**✅ Stores Data** : Holds values like numbers, text or objects.

**✅ Reusability** : Once stored the data can be used multiple times.

**✅ Dynamic Typing** : JavaScript variables do not require a fixed type they can hold different types of values at different times.

**✅ Memory Allocation** : The browser automatically manages memory for variables.

### 🔹Declaring Variables in JavaScript

JavaScript provides **Three Ways** to declare variables:

1. **`var`** : Variable can be re-declared & updated. A global scope variable.

#### Example 01 :

```javascript
    var name = "Alice";
    console.log(name); // Output: Alice

    var name = "Bob"; // Allowed (var can be redeclared)
    console.log(name); // Output: Bob
```

**_Note_** : **`var`** allows redeclaration which can cause unexpected issues.

2. **`let`** : Variable cannot be re-declared but can be updated. A block scope variable.

#### Example 01 :

```javascript
    let age = 25;
    console.log(age); // Output: 25

    age = 30; // Allowed (value can change)
    console.log(age); // Output: 30

    // let age = 35; ❌ Error: Cannot redeclare 'age' in the same scope
```

**_Note_**: **`let`** prevents redeclaration but allows reassignment.

The **`let`** keyword is **block-scoped**, meaning variables declared with **`let`** exist only **inside the block** **`{}`** where they are defined. **`let`** variables are block-scoped, meaning they exist only inside **`{}`**. Cannot be accessed outside the block where they are declared.

#### Example 02 : `let` Inside a Block `{}`

```javascript
    {
        let message = "Hello, World!";
        console.log(message); // Output: Hello, World!
    }
    console.log(message); // Error: message is not defined
```

✔ The variable **`message`** exists only inside the block **`{}`**

✔ Trying to access **`message`** outside the block results in an error.

1. **`const`** : Variable cannot be re-declared or updated. A block scope variable.

```javascript
    const PI = 3.1416;
    console.log(PI); // Output: 3.1416

    // PI = 3.14; Error: Cannot reassign a 'const' variable
```

**_Note_** : **`const`** is used for values that should not change.

#### 📌 Summary Table

<div align="center">

| Keyword | Scope    | Redeclaration | Reassignment | Hoisting                    |
| ------- | -------- | ------------- | ------------ | --------------------------- |
| `var`   | Function | Yes           | Yes          | Hoisted with `undefined`    |
| `let`   | Block    | No            | Yes          | Hoisted but not initialized |
| `const` | Block    | No            | No           | Hoisted but not initialized |

</div>

#### 📌 Best Practices

✔ Use **`const`** by default unless the value needs to change.

✔ Use **`let`** when reassignment is needed.

✔ Avoid **`var`** to prevent scope-related issues.

**_Note_** : **`let`** & **`const`** help write **cleaner** and **safer** JavaScript code!

### 🔹Variable Naming Rules

> **Allowed**

✔ Can contain letters, digits, underscores **`_`** & dollar signs **`$`**.

✔ Must start with a letter, **`_`** or **`$`**

✔ Case-sensitive (**`name`** and **`Name`** are different).

> **Not Allowed**

❌ Cannot start with a number.

❌ Cannot use reserved JavaScript keywords (like **`var`**, **`let`**, **_`function`_**).

## 📌 Dynamically Typed Language

Dynamic Typing means that variables in JavaScript do not have a fixed data type. A variable can hold different types of values during execution.

### 🔹Example of Dynamic Typing

```bash
    value = "Hello";       # String (changed type)
    console.log(value);    # Output: Hello

    value = true;          # Boolean (changed type again)
    console.log(value);    # Output: true
```

✔ A single variable can change its type at runtime.

✔ No need to specify data types when declaring variables.

## 🔹 Key Features of Dynamic Typing

✅ No need to declare a specific type (string, number, etc.).

✅ The type of a variable can change at runtime.

✅ Flexible but can lead to unexpected bugs if not handled properly.

**_Note :_** Dynamic typing makes JavaScript flexible but requires careful handling to prevent type-related errors!

## 📌 Data Types in JavaScript

JavaScript has Two main categories of data types:

1. **Primitive Data Types**
2. **Non-Primitive (Reference) Data Types**
<div align="center">
    <img src="Images/Data-Types.png" width=90%>
</div>

### 1. 🔹Primitive Data Types

These are the basic types that hold simple data and are immutable (cannot be changed directly). When we assign a primitive value to a variable the value is copied. There are 7 Types of Primitive Data Types.

<div align="center">
    <img src="Images/Primitive-Data-Types.png" width=90%>
</div>

#### 01. Number

- Represents both **Integers** & **Floating-Point** numbers.
- Examples: 10, 3.14

> **Example**

```javascript
    let age = 25;   // Integer
    let price = 99.99;  // Float
```

#### 02. String

- Represents sequences of characters (text).
- Examples: **`"Hello"`**, **`'World'`**
  > **Example**

```javascript
    let name = "Alice";
    let greeting = 'Hello, world!';
```

#### 03. Boolean

- Represents a **true** or **false** value.

```javascript
    let isTrue = true;
    let isFalse = false;
```

#### 04. Undefined

- A variable that has been declared but not assigned a value.
- Default value for uninitialized variables.

```javascript
    let value; // Undefined by default
```

#### 05. Null

- Represents intentional absence of any value.

```javascript
    let user = null;
```

#### 06. BigInt (ES11+)

- Used to represent large integers that cannot be handled by the Number type.

```javascript
    let bigNum = 1234567890123456789012345678901234567890n;
```

#### 07. Symbol (ES6+)

- A unique, immutable value often used for object property keys.
- Primarily used for unique identifiers.

```javascript
    let id = Symbol('id');
```

### 2. 🔹Non-Primitive (Reference) Data Types

These are **complex types** that hold collections of data. Variables assigned to reference types store a reference (or pointer) to the data rather than the data itself. Changes to the data are reflected across all references.

<div align="center">
    <img src="Images/Non-Primitive-Data-Types.png" width=90%>
</div>

#### 01. Object

- A collection of key-value pairs (properties).
- Can store multiple values of different data types.
<div align="center">
    <img src="Images/Objects.png" width=70%>
</div>

```javascript
    let person = {
    name: "Alice",
    age: 25,
    isMember: true
    };
```

#### 02. Array

- An ordered list of values.
- Can store values of any data type.

```javascript
    let numbers = [1, 2, 3, 4, 5];
    let fruits = ["Apple", "Banana", "Cherry"];
```

#### 03. Function

- Functions are also objects in JavaScript.
- Used to define reusable code.

```javascript
    function greet() {
    console.log("Hello!");
    }
```

### Print Object Values in JavaScript

In JavaScript, we can print an object’s values using different methods depending on the format we need.

#### 01 Using `console.log()` (Simple Output)

✔ Prints the entire object in the console.

```javascript
    let person = { name: "Alice", age: 25, city: "New York" };
    console.log(person);
```

#### 02. Accessing Individual Properties

✔ Prints specific property values using dot notation (**`.`**).

```javascript
    console.log(person.name);  // Output: Alice
    console.log(person.age);   // Output: 25
    console.log(person.city);  // Output: New York
```

#### 03. Using Bracket Notation [] (When Property Name is Dynamic or Special)

✔ Useful when the key is stored in a variable or has special characters.

```javascript
    console.log(person["name"]);  // Output: Alice
    console.log(person["age"]);   // Output: 25
```

#### 04. Using `Object.values()` (Get Only Values)

✔ Extracts and prints only the values of an object.

```javascript
    console.log(Object.values(person));
    // Output: [ 'Alice', 25, 'New York' ]
```

<div align ="center">

## Summary Table

| Data Type | Category      | Description                      | Examples                                    |
| --------- | ------------- | -------------------------------- | ------------------------------------------- |
| Number    | Primitive     | Numeric values (Integer & Float) | `10`, `3.14`, `-5`                          |
| String    | Primitive     | Text data                        | `"Hello"`, `'World'`                        |
| Boolean   | Primitive     | True or false                    | `true`, `false`                             |
| Undefined | Primitive     | Variable not assigned a value    | `let x;`                                    |
| Null      | Primitive     | Intentional absence of value     | `null`                                      |
| Symbol    | Primitive     | Unique identifier                | `Symbol('id')`                              |
| BigInt    | Primitive     | Large integer                    | `1234567890123456789012345678901234567890n` |
| Object    | Non-Primitive | Collection of key-value pairs    | `{ name: "Alice", age: 25 }`                |
| Array     | Non-Primitive | Ordered list of values           | `[1, 2, 3]`, `["Apple", "Banana"]`          |
| Function  | Non-Primitive | Reusable block of code           | `function() { return "Hi"; }`               |

</div>

### 📌 Key Differences

- Primitive Data Types are immutable and directly store values.
- Non-Primitive Data Types are mutable and store a reference to the value.

**_Note_** : Primitive types are simpler and more efficient, while non-primitive types are more flexible for complex data structures.

### Check the Type of a Data Type in JavaScript

In JavaScript, we can use the **`typeof`** operator to check the type of a variable or expression. This helps us determine whether a value is a string, number, object, etc.

#### Example 1: Checking Primitive Data Types

```javascript
    let age = 25;
    console.log(typeof age);  // Output: number

    let name = "Alice";
    console.log(typeof name); // Output: string

    let isActive = true;
    console.log(typeof isActive); // Output: boolean

    let user = null;
    console.log(typeof user);  // Output: object (special case in JS)

    let value;
    console.log(typeof value);  // Output: undefined
```

#### Example 2: Checking Non-Primitive Data Types

```javascript
    let person = { name: "Alice", age: 25 };
    console.log(typeof person);  // Output: object

    let numbers = [1, 2, 3];
    console.log(typeof numbers);  // Output: object (arrays are also objects in JS)

    function greet() {
    console.log("Hello!");
    }
    console.log(typeof greet);  // Output: function
```

**_Note_** : Despite being a primitive value representing "no value," **`typeof null`** returns **`"object"`**. This is a known JavaScript quirk.

## 📌 Comments in JavaScript

Comments in JavaScript help us write explanations within the code. They are ignored by the JavaScript engine & do not affect execution.

### 01. Single-Line Comment (`//`)

Used for short explanations or disabling a single line of code. Anything after **`//`** is ignored by JavaScript.

```javascript
    // This is a single-line comment
    let message = "Hello, World!"; // Another comment after code
```

### 2. Multi-Line Comment (`/* ... */`)

Used for longer explanations or temporarily disabling multiple lines of code. Everything inside **`/* ... */`** is ignored by JavaScript.

```javascript
    /* This is a multi-line comment.
   It can span multiple lines.
   Useful for detailed explanations. */
    let x = 10;
```

### Best Practices for Comments

✔ Keep them short & meaningful

✔ Use comments to explain why, not what (code should be self-explanatory)

✔ Avoid excessive comments that clutter code

✔ Use TODO comments for future improvements

## 📌 Operators in JavaScript

Operators in JavaScript are symbols that perform operations on values and variables. They can be used for mathematical calculations, comparisons, logical operations & more.

<div align="center">
    <img src="Images/Operators.png" width=50%>
</div>

### 1. Arithmetic Operators

Used for performing basic mathematical calculations.

<div align="center">
    
| Operator | Description | Example | Output |
|---|---|---|---|
| `+` | Addition | `5 + 3` | `8` |
| `-` | Subtraction | `10 - 4` | `6` |
| `*` | Multiplication | `6 * 2` | `12` |
| `/` | Division | `9 / 3` | `3` |
| `%` | Modulus (Remainder) | `10 % 3` | `1` |
| `**` | Exponentiation | `2 ** 3` | `8` |

</div>

> **Arithmetic Operator Example**

```javascript
    let a = 10, b = 3;
    console.log(a + b); // Output: 13
    console.log(a - b); // Output: 7
    console.log(a * b); // Output: 30
    console.log(a / b); // Output: 3.33
    console.log(a % b); // Output: 1
    console.log(a ** b); // Output: 1000
```

### 2. Increment & Decrement Operators

Increment (**`++`**) & decrement (**`--`**) operators are unary operators that modify a variable's value by 1.

#### Increment (`++`)

It adds **`1`** to a variable.
There are two types:

1. **Pre-Increment (`++x`)**
   Increases the value before returning it.
   ```javascript
        let a = 5;
        console.log(++a);  // Output: 6 (a is incremented first)
        console.log(a);    // Output: 6 (final value of a)
   ```
2. **Post-Increment (`x++`)**
   Returns the current value before increasing it.
   ```javascript
        let b = 5;
        console.log(b++);  // Output: 5 (returns old value, then increments)
        console.log(b);    // Output: 6 (final value of b)
   ```

#### Decrement (`--`)

It subtracts **`1`** from a variable.
There are two types:

1. **Pre-Decrement (`--x`)**
   Decreases the value before returning it.
   ```javascript
        let c = 5;
        console.log(--c);  // Output: 4 (c is decremented first)
        console.log(c);    // Output: 4 (final value of c)
   ```
2. **Post-Decrement (`x--`)**
   Returns the current value before decreasing it.
   ```javascript
        let d = 5;
        console.log(d--);  // Output: 5 (returns old value, then decrements)
        console.log(d);    // Output: 4 (final value of d)
   ```
