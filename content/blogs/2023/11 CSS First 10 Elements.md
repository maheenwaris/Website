---
title: "Introduction to the First 10 CSS Elements"
author: "Maheen Waris"
description: ""
url: "/blogs/Introduction-to-the-First-10-CSS-Elements"
date: "2023-09-11"
tags: [Development", "CSS", "Styling", "Coding"]
draft: "false"
toc: "true"
---

## An Introduction to the First 10 CSS Elements

Cascading Style Sheets (CSS) are a fundamental part of web development. I already write about css in my earlier article [Beginner's guide to CSS](https://maheenwaris.pages.dev/blogs/Beginner%27s-Guide-to-CSS/). CSS consists of various elements and properties, we'll focus on the first 10 CSS elements that every web developer should know. These elements form the basis of styling web pages for creating beautiful and responsive designs.

### 1. Selector

A CSS selector is the first element you encounter when styling a web page. Selectors are used to target HTML elements to apply styles. They can target elements by their tag name, class, ID, or other attributes. For example, to target all paragraphs in an HTML document, you would use the selector `p`.

### 2. Property

CSS properties determine what aspect of an element you want to style. Common properties include `color` (text color), `font-size` (text size), `background-color` (background color), and `border` (border style). Properties are assigned values to define the specific style you want to apply.

### 3. Value

Values are assigned to properties to specify the desired style. For instance, to set the text color to red, you would use the value `red`. Values can be numerical (e.g., `20px` for font size) or textual (e.g., `solid` for border style).

### 4. Declaration

A declaration is a combination of a property and its corresponding value, enclosed in curly braces `{}`. Declarations are used within CSS rules to define how selected elements should be styled. Here's an example of a declaration:

```css
color: blue;
```

### 5. Rule

A CSS rule is a set of one or more declarations that define how a specific set of HTML elements should be styled. Rules are typically written in a separate CSS file or within a `<style>` tag in an HTML document. Here's an example of a CSS rule:

```css
p {
  color: green;
  font-size: 18px;
}
```

### 6. Selector and Declaration Block

A CSS rule consists of a selector followed by a declaration block enclosed in curly braces `{}`. The declaration block contains one or more declarations that specify the styles for the selected elements.

### 7. Class Selector

The class selector is used to target HTML elements with a specific class attribute. It is denoted by a period (`.`) followed by the class name. For example, to target all elements with the class "highlight," you would use the selector `.highlight`.

```html
<style>
  .highlight {
    color: yellow;
  }
</style>
<p class="highlight">Here's an example.</p>
```

### 8. ID Selector

The ID selector targets a single HTML element with a specific ID attribute. It is denoted by a hash (`#`) followed by the ID name. ID selectors should be unique within a document to ensure they target only one element. For example, to target an element with the ID "header," you would use the selector `#header`.

```html
<style>
  #para {
    color: brown;
  }
</style>
<p id="para">Here's an example</p>
```

### 9. Universal Selector

The universal selector (`*`) targets all HTML elements on a page. It is often used to apply styles globally. While it can be useful, it should be used sparingly to avoid unintended consequences.

### 10. Descendant Selector

A descendant selector allows you to target elements that are descendants of a specific parent element. It uses space to separate the parent and child elements. For example, to target all `<a>` elements that are descendants of a `<div>` with the class "menu," you would use the selector `.menu a`.

<hr>

### Conclusion

These first 10 CSS elements provide a solid foundation for styling web pages. Understanding selectors, properties, values, declarations, rules, and the different types of selectors (class, ID, universal, and descendant) is essential for creating visually appealing and responsive web designs.

---
