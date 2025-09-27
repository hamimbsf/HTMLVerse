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

## HTML Attributes

**Attributes** in HTML provide **extra information** about an element.
They are always defined in the **opening tag** and usually come in a **name="value"** pair.

## ✅ Key Points

- Attributes modify the behavior of HTML elements.
- They are written inside the opening tag.
- Most attributes have a **name** and a **value**.

## 🔹 Examples

### 1. Image with attributes

```html
<img src="cat.jpg" alt="A cute cat" />
```

- src → specifies the image source (file path or URL).

- alt → alternative text if the image fails to load.

### 2. Link with attributes

```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

- href → destination URL.

- target="\_blank" → opens the link in a new tab.

---

## HTML Tags vs HTML Elements

## 🔖 HTML Tags

- Tags are the **keywords inside angle brackets** (`< >`) in HTML.
- They tell the browser **what type of content** it is.
- Usually come in pairs: **opening tag** and **closing tag**.

### Example:

```html
<p></p>
```

Here <p> is a tag.

## 🧩 HTML Elements

- An element = opening tag + content + closing tag.

- It represents the complete structure of the HTML component.

### Example:

```html
<p>Hello World</p>
```

- <p> → opening tag
- Hello World → content
- </p> → closing tag
- Together → HTML element

---

## Difference Between `<div>` and `<span>`

## 🔹 `<div>` (Division Tag)

- **Block-level element**.
- Takes up the **full width** available.
- Always starts on a **new line**.
- Commonly used for **grouping larger sections** of HTML elements.

### Example:

```html
<div>
  <h1>Title</h1>
  <p>This is a paragraph inside a div.</p>
</div>
```

## 🔹 <span>

- Inline element.
- Takes up only as much width as its content.
- Does not start on a new line.
- Commonly used to style small parts of text or content inside other elements.

```html
<p>This is a <span style="color: red;">red word</span> in a sentence.</p>
```

---

## Difference Between Inline Elements and Block-Level Elements

## 🔹 Block-Level Elements

- Always start on a **new line**.
- Take up the **full width** available (by default).
- Can contain **other block-level and inline elements**.
- Used for structuring the **layout** of the page.

### Examples:

`<div>`, `<p>`, `<h1>–<h6>`, `<ul>`, `<li>`, `<section>`, `<article>`, `<footer>`

```html
<div>
  <h1>Heading</h1>
  <p>This is a paragraph inside a block element.</p>
</div>
```

## 🔹 Inline Elements

- Do **not** start on a new line.
- Take up **only as much width** as their content.
- Can contain **only text or other inline elements** (not block elements).
- Used for **styling or grouping small pieces of content**.

## ✅ Examples

- `<span>`
- `<a>`
- `<strong>`
- `<em>`
- `<img>`
- `<label>`

### Example Code:

```html
<p>This is <span style="color: red;">red text</span> inside a sentence.</p>
```

---

## 1. What is `<!DOCTYPE html>` and why do we use it?

- `<!DOCTYPE html>` is a **declaration** that tells the browser which version of HTML the document is using.
- In modern HTML5, it is simply written as:

  ```html
  <!DOCTYPE html>
  ```

### Purpose:

- Ensures the browser renders the page in standards-compliant mode.
- Helps avoid quirks mode (inconsistent rendering across browsers).

---

## 2. What is the difference between `<head>` and `<body>`?

### `<head>`:

- Contains **metadata** (information about the document, not displayed on the page).
- Includes:
  - `<title>` → page title shown in browser tab
  - `<meta>` → character set, description, keywords, viewport, etc.
  - `<link>` → CSS, fonts, external resources
  - `<script>` → JavaScript references (usually for head-level config)

---

### `<body>`:

- Contains the **content that is visible** to users.
- Includes:
  - Text, images, videos, links
  - Headings, paragraphs, forms
  - Interactive elements

---

## 3. What is the `<title>` tag used for?

- The `<title>` tag defines the **title of the HTML document**.
- It appears in:
  - The **browser tab**
  - **Search engine results** (important for SEO)
  - **Bookmarks/favorites**

### Example:

```html
<head>
  <title>My Portfolio</title>
</head>
```

---

# Difference Between HTML and XHTML

| Feature                 | HTML                                                                 | XHTML                                                                      |
| ----------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Full Form**           | HyperText Markup Language                                            | eXtensible HyperText Markup Language                                       |
| **Based On**            | SGML (Standard Generalized Markup Language)                          | XML (eXtensible Markup Language)                                           |
| **Syntax Rules**        | More flexible, forgiving. Browsers can render even with some errors. | Strict syntax rules. Must be well-formed, else browsers may not render it. |
| **Case Sensitivity**    | Tag names are **not case-sensitive** (`<body>` = `<BODY>`)           | Tag names **must be lowercase** (`<body>`)                                 |
| **Tag Closing**         | Optional for some tags (`<br>` can be written alone)                 | All tags must be properly closed (`<br />`)                                |
| **Attribute Quotation** | Quotes around attribute values are optional (`<input type=text>`)    | Attribute values **must be quoted** (`<input type="text" />`)              |
| **Error Handling**      | Browsers try to fix errors automatically                             | Strict; even minor errors can prevent rendering                            |
| **Example**             | `<img src="image.jpg">`                                              | `<img src="image.jpg" />`                                                  |
| **Popularity**          | More widely used historically                                        | Less common now, mainly for stricter or XML-based applications             |

**Key Idea:**

- **HTML** is flexible and forgiving.
- **XHTML** is stricter because it follows XML rules, which ensures well-formed documents.

---

## Semantic Tags in HTML5

**Semantic tags** in HTML5 are tags that **clearly describe their meaning and the type of content they contain**. They make the structure of a webpage more understandable for **browsers, developers, and search engines**.

---

## Key Points

1. Semantic tags **give meaning** to the content inside them.
2. They improve **accessibility** (for screen readers) and **SEO** (search engine optimization).
3. They **replace generic `<div>` tags** when the purpose of the content can be described.

---

## Common Semantic Tags

| Tag                         | Purpose                                                                                           |
| --------------------------- | ------------------------------------------------------------------------------------------------- |
| `<header>`                  | Defines the header of a page or section. Usually contains navigation, logo, or title.             |
| `<footer>`                  | Defines the footer of a page or section. Usually contains copyright info, links, or contact info. |
| `<nav>`                     | Defines navigation links.                                                                         |
| `<main>`                    | Represents the main content of the document.                                                      |
| `<article>`                 | Represents a self-contained piece of content, like a blog post, news article, or forum post.      |
| `<section>`                 | Represents a thematic grouping of content, usually with a heading.                                |
| `<aside>`                   | Represents content that is tangentially related, like a sidebar or pull quote.                    |
| `<figure>` & `<figcaption>` | `<figure>` contains media (image, chart, etc.) and `<figcaption>` provides a caption for it.      |
| `<mark>`                    | Highlights text that is relevant or important.                                                    |

---

## Example

```html
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
    </nav>
  </header>

  <main>
    <article>
      <h2>Blog Post Title</h2>
      <p>This is a blog post content...</p>
    </article>

    <aside>
      <h3>Related Links</h3>
      <p>Some sidebar content...</p>
    </aside>
  </main>

  <footer>
    <p>© 2025 My Website</p>
  </footer>
</body>
```

---

# Difference Between <b> & <strong>, <i> & <em>

---

## 1. `<b>` vs `<strong>`

| Tag        | Purpose             | Semantic Meaning                   | Example                           |
| ---------- | ------------------- | ---------------------------------- | --------------------------------- |
| `<b>`      | Makes text **bold** | No semantic meaning; purely visual | `<b>Bold Text</b>`                |
| `<strong>` | Makes text **bold** | Indicates **important** text       | `<strong>Important Text</strong>` |

**Key:**

- `<b>` → just styling.
- `<strong>` → conveys importance to browsers, search engines, and assistive technologies.

---

## 2. `<i>` vs `<em>`

| Tag    | Purpose               | Semantic Meaning                   | Example                    |
| ------ | --------------------- | ---------------------------------- | -------------------------- |
| `<i>`  | Makes text **italic** | No semantic meaning; purely visual | `<i>Italic Text</i>`       |
| `<em>` | Makes text **italic** | Indicates **emphasis**             | `<em>Emphasized Text</em>` |

**Key:**

- `<i>` → just styling.
- `<em>` → emphasizes text for meaning and accessibility.

---

## Example

```html
<p>This is <b>bold</b> but not important.</p>
<p>This is <strong>bold and important</strong>.</p>

<p>This is <i>italic</i> but neutral.</p>
<p>This is <em>italic and emphasized</em>.</p>
```

---

## Absolute vs Relative URLs in HTML

---

## 1. Absolute URL

- Specifies the **full path** to a resource, including the protocol and domain name.
- Works from anywhere because it points to the exact location on the internet.

**Example:**

```html
<a href="https://www.example.com/about.html">About Us</a>
<img src="https://www.example.com/images/logo.png" alt="Logo" />
```

## 2. Relative URL

- Specifies a path relative to the current page.
- Depends on the location of the current file; may break if the file is moved.

**Example:**

1. Relative to current folder:

```html
<a href="about.html">About Us</a> <img src="images/logo.png" alt="Logo" />
```

2. Relative to parent folder:

```html
<a href="../contact.html">Contact</a>
```

3. Relative to root folder:

```html
<a href="/home/index.html">Home</a>
```

---

## HTML Forms and Input Types

## 1. How to Create a Form in HTML

A form in HTML is created using the `<form>` tag. It is used to collect user input.

**Basic Syntax:**

```html
<form action="submit_page.html" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Enter your name" />

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" />

  <input type="submit" value="Submit" />
</form>
```

### Attributes of <form>:

- action → URL where the form data will be sent.
- method → HTTP method, usually get or post.
- enctype → encoding type for file uploads (multipart/form-data).

## 2. Input Types in HTML5

HTML5 introduced new input types to improve user experience and validation.

**Common input types:**

| Type             | Description                                |
| ---------------- | ------------------------------------------ |
| `text`           | Single-line text input                     |
| `password`       | Password field (masked input)              |
| `email`          | Email input with validation                |
| `number`         | Numeric input with optional min, max, step |
| `tel`            | Telephone number input                     |
| `url`            | URL input with validation                  |
| `date`           | Date picker                                |
| `time`           | Time picker                                |
| `datetime-local` | Date and time input without timezone       |
| `range`          | Slider input                               |
| `color`          | Color picker                               |
| `checkbox`       | Checkbox selection                         |
| `radio`          | Radio button selection                     |
| `file`           | File upload input                          |
| `submit`         | Submit button                              |
| `reset`          | Reset button                               |
| `button`         | Generic button                             |

---

## 3. Difference Between `<button>` and `<input type="button">`

| Feature          | `<button>`                                       | `<input type="button">`                   |
| ---------------- | ------------------------------------------------ | ----------------------------------------- |
| Content          | Can contain text, HTML, or images                | Only text (value attribute)               |
| Default behavior | If type is omitted, defaults to `submit`         | Only acts as a button (no default submit) |
| Flexibility      | More flexible, can include icons or styling      | Less flexible, plain button text          |
| Example          | `<button type="button"><b>Click Me</b></button>` | `<input type="button" value="Click Me">`  |

---

## HTML5 New Features

HTML5 introduced many new features to improve web development, interactivity, and multimedia support.

## 1. New Semantic Elements

HTML5 added semantic tags to structure content more meaningfully:

| Element                     | Purpose                                                  |
| --------------------------- | -------------------------------------------------------- |
| `<header>`                  | Defines a header section for a page or section           |
| `<footer>`                  | Defines a footer section for a page or section           |
| `<nav>`                     | Defines navigation links                                 |
| `<article>`                 | Defines self-contained content (like blog posts)         |
| `<section>`                 | Defines a thematic section of content                    |
| `<aside>`                   | Defines content aside from main content (like a sidebar) |
| `<main>`                    | Defines the main content of a page                       |
| `<figure>` & `<figcaption>` | Used for images with captions                            |

---

## 2. New Form Features

HTML5 improved forms with:

- New input types: `email`, `url`, `number`, `date`, `time`, `color`, `range`, `tel`, `datetime-local`
- New attributes: `placeholder`, `required`, `pattern`, `autofocus`, `autocomplete`, `formnovalidate`
- Built-in form validation without JavaScript

---

## 3. Multimedia Elements

HTML5 allows embedding audio and video natively:

- `<audio>` → Embed audio files
- `<video>` → Embed video files
- `<source>` → Provide multiple media sources for audio/video

---

## 4. Graphics and Visuals

- `<canvas>` → Draw graphics, charts, and animations via JavaScript
- `<svg>` → Scalable vector graphics for images and shapes

---

## 5. APIs and Browser Features

HTML5 comes with powerful APIs for web apps:

- **Geolocation API** → Access user's location
- **Web Storage** → `localStorage` and `sessionStorage` for storing data on the browser
- **Web Workers** → Run background scripts for performance
- **Drag & Drop API** → Enable drag-and-drop functionality
- **History API** → Manipulate browser history
- **Offline & Application Cache** → Build offline-capable apps
- **WebSocket API** → Real-time communication

---

## 6. Other Features

- Support for new document types: `<!DOCTYPE html>`
- Cleaner syntax, removing many deprecated tags and attributes (`<font>`, `<center>`, etc.)
- Better accessibility support
- Enhanced semantic structure for search engines and SEO

---

## Difference Between `<section>`, `<article>`, and `<div>`

| Tag         | Purpose                                                        | When to Use                                                                                            | Notes                                                                                  |
| ----------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| `<section>` | Defines a thematic grouping of content, usually with a heading | Use for sections of a page that have a common theme, like chapters, tabs, or grouped topics            | Semantically meaningful, improves accessibility and SEO                                |
| `<article>` | Represents self-contained content that can stand alone         | Use for blog posts, news articles, forum posts, or any content that could be distributed independently | Semantically meaningful, ideal for syndication                                         |
| `<div>`     | Generic container with no semantic meaning                     | Use purely for styling, layout, or scripting purposes                                                  | Does **not** convey meaning; should be avoided for content that has semantic relevance |

**Key Differences:**

- `<section>` and `<article>` are **semantic elements**; `<div>` is not.
- `<article>` is usually self-contained; `<section>` is part of a bigger page structure.
- `<div>` is only for grouping content for CSS/JS purposes, no semantic meaning.

---

# Local Storage vs Session Storage in HTML5

HTML5 introduced **Web Storage API** to store data on the client-side, which is faster and easier than using cookies.

## 1. Local Storage

- Stores data **persistently** in the browser.
- Data **does not expire** until explicitly deleted.
- Data is **shared across all tabs/windows** of the same origin.

**Example:**

```javascript
// Save data
localStorage.setItem("username", "Hamim");

// Retrieve data
let user = localStorage.getItem("username");

// Remove data
localStorage.removeItem("username");

// Clear all data
localStorage.clear();
```

## 2. Session Storage

- Stores data temporarily for a single browser tab/session.
- Data expires when the tab or browser is closed.
- Data is not shared across tabs.

**Example:**

```javascript
// Save data
sessionStorage.setItem("sessionName", "ChatGPT Session");

// Retrieve data
let sessionUser = sessionStorage.getItem("sessionName");

// Remove data
sessionStorage.removeItem("sessionName");

// Clear all data
sessionStorage.clear();
```

---

## `<canvas>` vs `<svg>` in HTML5

HTML5 introduced **`<canvas>`** and **`<svg>`** for drawing graphics on web pages.

---

## 1. `<canvas>`

- A **bitmap-based** drawing area.
- Graphics are drawn using **JavaScript**.
- Suitable for **dynamic, pixel-based rendering**, like games, animations, charts.
- Once drawn, individual elements **cannot be accessed or modified directly**.
- Resolution depends on the canvas size (can get pixelated if scaled).

## 2. `<svg>`

- A vector-based graphic format (Scalable Vector Graphics).
- Graphics are defined using XML/HTML tags.
- Suitable for icons, diagrams, charts, and anything that should scale without losing quality.
- Individual elements can be accessed, styled, and animated via CSS and JavaScript.

---

## Difference Between `id` and `class` Attributes

| Feature         | `id`                                          | `class`                                                              |
| --------------- | --------------------------------------------- | -------------------------------------------------------------------- |
| Uniqueness      | Must be **unique** within a page              | Can be used on **multiple elements**                                 |
| Purpose         | Identify a single element                     | Group multiple elements together                                     |
| Selector in CSS | `#idName`                                     | `.className`                                                         |
| Selector in JS  | `document.getElementById('idName')`           | `document.getElementsByClassName('className')`                       |
| Use Case        | Target a specific element (e.g., main header) | Apply styles or scripts to multiple elements (e.g., buttons, cards)  |
| HTML Example    | `<div id="header">Header</div>`               | `<div class="card">Card 1</div>`<br>`<div class="card">Card 2</div>` |

**Key Points:**

- Use `id` when you need to **uniquely identify an element**.
- Use `class` when you want to **style or manipulate multiple elements** in the same way.
- An element can have **both `id` and `class`** at the same time:

```html
<div id="main-header" class="header card">Welcome</div>
```

---

# ARIA in HTML (Accessibility)

**ARIA** stands for **Accessible Rich Internet Applications**.
It is a set of **attributes that improve web accessibility** for users with disabilities, especially those using **screen readers** or other assistive technologies.

---

## 1. Purpose of ARIA

- Makes web content more **accessible** to people with disabilities.
- Provides **semantic meaning** to elements that are otherwise non-semantic.
- Helps assistive technologies **understand custom widgets, dynamic content, and complex UI components**.

---

## 2. Common ARIA Attributes

| Attribute         | Purpose                                                                         |
| ----------------- | ------------------------------------------------------------------------------- |
| `role`            | Defines the type of element (e.g., `button`, `navigation`, `dialog`)            |
| `aria-label`      | Provides a **text label** for an element (used when visible text is missing)    |
| `aria-labelledby` | References another element that **labels this element**                         |
| `aria-hidden`     | Hides content from assistive technologies (`true` or `false`)                   |
| `aria-expanded`   | Indicates whether a **collapsible element** is expanded or collapsed            |
| `aria-checked`    | Shows the **state of checkboxes or toggle buttons**                             |
| `aria-live`       | Announces **dynamic content changes** to screen readers (`polite`, `assertive`) |

---

## 3. Example

```html
<button role="button" aria-label="Close dialog" onclick="closeDialog()">
  ✖
</button>

<div role="alert" aria-live="assertive">Form submitted successfully!</div>
```

**Explanation:**

- The role="button" tells assistive tech that this element is a button.
- aria-label="Close dialog" gives a readable name for the button.
- role="alert" and aria-live="assertive" announce dynamic messages immediately.
