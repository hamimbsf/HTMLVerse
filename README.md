# Introduction to HTML

---

# Why HTML Was Made

HTML (**HyperText Markup Language**) was created to **share documents over the internet**.

- In **1989–1990**, Tim Berners-Lee, a scientist at **CERN (European Organization for Nuclear Research)**, needed a way for researchers to **share information across different computers and locations**.
- Before HTML, scientists sent files by **email** or used **proprietary systems** that weren’t compatible.
- HTML was designed to be **simple, universal, and readable** by both humans and computers.

---

# How HTML Was Made

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

# Political or Other Reasons?

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

# HTML Tags

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

# What is the `<body>` Tag?

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
