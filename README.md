# Introduction to HTML

---

## Why HTML Was Made

HTML (**HyperText Markup Language**) was created to **share documents over the internet**.

- In **1989–1990**, Tim Berners-Lee, a scientist at **CERN (European Organization for Nuclear Research)**, needed a way for researchers to **share information across different computers and locations**.
- Before HTML, scientists sent files by **email** or used **proprietary systems** that weren’t compatible.
- HTML was designed to be **simple, universal, and readable** by both humans and computers.

---

## How HTML Was Made

### Tim Berners-Lee’s Idea

- He wanted a system of **hypertext**, where text can link to other text or documents.
- He combined three things:
  1. **HTML** → markup for formatting documents
  2. **HTTP** → HyperText Transfer Protocol to transfer documents
  3. **URL** → Uniform Resource Locator to locate documents

### First Web Page

- In **1991**, the **first web page** was created at CERN.
- It explained **what the World Wide Web was** and included links to other pages.

### Simplicity

- HTML was designed to be **easy to write and read**.
- Only a few tags at first, mainly for **headings, paragraphs, and links**.

---

## Political or Other Reasons?

- No **political agenda** was behind HTML.
- The main driver was **scientific collaboration** — CERN wanted researchers to **share knowledge freely**.
- Tim Berners-Lee always aimed to keep the **web open and free**, not controlled by any government or company.
- Later, standards organizations (like **W3C**) formalized HTML to ensure it was **universal and neutral**.

---

## 1. Why We Use HTML?

- To **create web pages** and display content in a browser.
- It gives **structure** to text, images, videos, and links.
- Without HTML, a browser wouldn’t know how to show content.

---

## 2. What is HTML?

- **HTML** = **HyperText Markup Language**.
- It is not a programming language; it’s a **markup language**.
- It tells the browser how to display content using **tags** (like `<h1>`, `<p>`, `<img>`).

---

## 3. How to Write HTML?

HTML documents are written using **tags**.
Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first HTML page.</p>
  </body>
</html>
```

---

## 4. Where We Write HTML?

- In a **text editor** (like VS Code, Sublime Text, Notepad).
- Save the file with a **`.html` extension** (e.g., `index.html`).
- Open it in a **web browser** (Chrome, Firefox, Edge, etc.) to see the result.

---

## 5. When We Use HTML?

- When creating **any web page**.
- For **structuring content** before adding styles (CSS) or interactivity (JavaScript).

### Example Use Cases:

- Building websites
- Creating forms
- Displaying images and videos
- Adding links and navigation

---

## HTML Tags

---

## What is a Tag in HTML?

- A **tag** in HTML is a special keyword written inside angle brackets `< >`.
- Tags tell the browser **how to display content**.
- Most tags come in pairs:
  - **Opening tag:** `<p>`
  - **Closing tag:** `</p>`
- Example:
  ```html
  <p>This is a paragraph.</p>
  ```

---

## Why We Use the `<head>` Tag?

The `<head>` tag contains **metadata** (information about the page, not visible to users).

### Common things inside `<head>`:

- `<title>` → Page title (shows in browser tab).
- `<meta>` → Information like keywords, description, character set.
- `<link>` → Linking external files like CSS.
- `<script>` → Adding JavaScript files.

👉 **Example:**

```html
<head>
  <title>My Website</title>
  <meta charset="UTF-8" />
  <link rel="stylesheet" href="style.css" />
</head>
```

---

## What is the `<title>` Tag?

The `<title>` tag defines the **title of the webpage**.

- It appears on the **browser tab**.
- It also shows up in **search engine results**.

👉 **Example:**

```html
<title>Welcome to HTMLVerse</title>
```

---

## What is the `<body>` Tag?

The `<body>` tag contains all the **visible content** of a webpage.

Everything you see in the browser (**text, images, videos, links**) goes inside `<body>`.

👉 **Example:**

```html
<body>
  <h1>Hello, World!</h1>
  <p>This is my first webpage.</p>
  <img src="image.jpg" alt="Sample image" />
</body>
```

---

## HTML Tags Overview

HTML tags are the **building blocks of a web page**. They define **how content is displayed** in the browser.

---

## How Many Important HTML Tags Exist?

- There are **over 100 HTML tags** in total.
- For beginners, focus on the **most commonly used tags**, such as:
  - `<html>` → Root of the page
  - `<head>` → Metadata
  - `<title>` → Page title
  - `<body>` → Visible content
  - `<h1>`–`<h6>` → Headings (total 6 heading)
  - `<p>` → Paragraphs
  - `<a>` → Links
  - `<img>` → Images
  - `<ul>` / `<ol>` → Lists
  - `<li>` → List items
  - `<div>` / `<span>` → Containers
  - `<form>` / `<input>` → Forms

---

## Why We Use HTML Tags

- To **structure content** for the browser.
- To make web pages **readable and accessible**.
- To **link documents**, add images, create lists, headings, and interactive forms.
- To separate **metadata** from **visible content**.

---

## When We Use HTML Tags

- Whenever we create a **web page**.
- For **structuring content** before adding styles (CSS) or interactivity (JavaScript).
- For **semantics**, accessibility, and search engine optimization.

---

## How We Use HTML Tags

- Tags are written using **angle brackets `< >`**.
- Most tags have **opening and closing tags**, e.g., `<p>...</p>`.
- Some tags are **self-closing**, e.g., `<img src="image.jpg" alt="description" />`.

### Example:

```html
<h1>My First Heading</h1>
<p>This is a paragraph.</p>
<a href="https://example.com">Visit Example</a>
<img src="image.jpg" alt="Sample image" />
```

---

## HTML Comments

---

## What is an HTML Comment?

- Comments are **notes in the code** that are **not displayed in the browser**.
- They are used to **explain code**, leave reminders, or temporarily disable parts of HTML.

---

## How to Write a Comment in HTML

- Use the following syntax:

```html
<!-- This is a comment -->
```

---
