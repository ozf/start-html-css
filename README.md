# HTML & CSS Starter Guide

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setting Up](#setting-up)
- [HTML Basics](#html-basics)
  - [HTML Structure](#html-structure)
  - [Common HTML Elements](#common-html-elements)
- [CSS Basics](#css-basics)
  - [CSS Syntax](#css-syntax)
  - [CSS Selectors](#css-selectors)
  - [Box Model](#box-model)
- [Responsive Design](#responsive-design)
- [Best Practices](#best-practices)
- [Resources](#resources)

## Introduction
Welcome to the HTML & CSS Starter Guide! This README will help you get started with web development using HTML and CSS.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
- A code editor (e.g., VSCode, Sublime Text)
- A web browser (e.g., Chrome, Firefox)

### Setting Up
1. Create a new project directory:
   ```sh
   mkdir my-web-project
   cd my-web-project
   ```
2. Create an `index.html` file and a `styles.css` file in the project directory.

## HTML Basics

### HTML Structure
HTML (HyperText Markup Language) is used to create the structure of web pages. A basic HTML structure looks like this:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

### Common HTML Elements
- **Headings**: `<h1>` to `<h6>`
- **Paragraphs**: `<p>`
- **Links**: `<a href="url">Link text</a>`
- **Images**: `<img src="image.jpg" alt="description">`
- **Lists**: `<ul>` (unordered), `<ol>` (ordered), `<li>` (list items) 

## CSS Basics

### CSS Syntax
CSS (Cascading Style Sheets) is used to style HTML elements. A basic CSS rule looks like this:
```css
selector {
    property: value;
}
```

### CSS Selectors
- **Element Selector**: `p { color: blue; }`
- **Class Selector**: `.classname { color: red; }`
- **ID Selector**: `#idname { color: green; }`
- **Attribute Selector**: `[type="text"] { border: 1px solid black; }`

### Box Model
The CSS box model describes the rectangular boxes that are generated for elements:
- **Content**: The actual content of the box, where text and images appear
- **Padding**: Clears an area around the content
- **Border**: A border that goes around the padding (if any) and content
- **Margin**: Clears an area outside the border

## Responsive Design
Responsive design ensures that web pages look good on all devices. Use media queries to apply different styles for different screen sizes:
```css
@media (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}
```

## Best Practices
- Keep your HTML semantic and well-structured
- Use external CSS for styling
- Ensure your site is responsive and accessible
- Optimize images and other assets
