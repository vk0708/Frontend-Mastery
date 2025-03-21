# Frontend-Mastery
[HTML](#HTML)

## Table of Contents
- [Introduction HTML](##HTML)
- [Introduction CSS](##introduction)
- [Advanced CSS](##advanced)

## HTML Notes

## Elements Used in the Portfolio Website

### 1. **Structural Elements**
- `<html>`: Root element of the HTML document
- `<head>`: Contains metadata, title, and styles
- `<body>`: Contains all visible content

### 2. **Metadata and Styling**
- `<meta charset="UTF-8">`: Defines character encoding
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Makes the page responsive
- `<title>`: Defines the webpage title
- `<style>`: Internal CSS for styling
- `@import url()`: Imports external Google Fonts

### 3. **Text Content Elements**
- `<h1>`, `<h2>`, `<h3>`: Headings for different sections
- `<p>`: Paragraphs for textual content
- `<strong>`: Bold text
- `<em>`: Italic text

### 4. **Navigation and Links**
- `<nav>`: Navigation bar
- `<ul>`, `<li>`: Unordered list for menu items
- `<a href="">`: Hyperlinks to different pages

### 5. **Multimedia Elements**
- `<img>`: Displays images (logo, service images, etc.)
- `<audio>`: Embedded audio player for podcasts
- `<source>`: Defines multiple audio formats
- `<iframe>`: Embeds Google Maps

### 6. **Forms and Inputs**
- `<form>`: Contact form
- `<input type="text">`, `<input type="email">`: Input fields for username and email
- `<textarea>`: Multiline input field for messages
- `<input type="submit">`: Submit button

### 7. **Interactive Elements**
- `<button>`: Buttons for actions like "See My Work" and "Visit YouTube"
- `<progress>`: Progress bars for skill levels

### 8. **Sections and Layout**
- `<section>`: Organizes content into sections (About, Services, Blog, Contact, etc.)
- `<div>`: Generic container for styling and structuring
- `<figure>` & `<figcaption>`: Used for images with captions

### 9. **Footer**
- `<footer>`: Footer section containing copyright information
<hr>

## CSS Tutorial

## Introduction to CSS
CSS (Cascading Style Sheets) is used to style HTML elements.
```css
body {
    background-color: lightgray;
}
```

## CSS Selectors
Selectors are used to target HTML elements.

- **Element Selector:** Targets elements by tag name.
    ```css
    p {
        color: blue;
    }
    ```
- **Class Selector:** Targets elements by class.
    ```css
    .myClass {
        font-size: 20px;
    }
    ```
- **ID Selector:** Targets a specific element by ID.
    ```css
    #myId {
        background-color: yellow;
    }
    ```

## CSS Properties
Common properties include:

- **Color:** Sets the text color.
    ```css
    color: red;
    ```
- **Font:** Defines text style.
    ```css
    font-family: Arial, sans-serif;
    ```
- **Margin & Padding:** Controls spacing.
    ```css
    margin: 10px;
    padding: 20px;
    ```

## CSS Layout
Layout techniques include:

- **Flexbox:** A flexible way to arrange elements.
    ```css
    display: flex;
    justify-content: center;
    ```
- **Grid:** A powerful layout system.
    ```css
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    ```

## Responsive Design
Using media queries for different screen sizes.
```css
@media (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}
```

## Advanced CSS
Explore advanced CSS techniques to enhance your designs.

- **CSS Variables:** Define reusable values.
    ```css
    :root {
        --primary-color: #3498db;
    }
    p {
        color: var(--primary-color);
    }
    ```
- **Transitions:** Smooth animations for elements.
    ```css
    button {
        transition: background-color 0.3s ease;
    }
    button:hover {
        background-color: #2980b9;
    }
    ```
- **Animations:** Create keyframe animations.
    ```css
    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }
    .box {
        animation: fadeIn 2s ease-in;
    }
    ```
- **Clipping & Masking:** Control element visibility.
    ```css
    .clip-text {
        clip-path: circle(50%);
    }
    
#### © 2025 VK0708

