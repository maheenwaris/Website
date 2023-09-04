---
title: "A Beginner's Guide to Creating a Navbar with HTML and CSS"
author: "Maheen Waris"
description: ""
url: "/blogs/Beginner's-Guide-to-Creating-Navbar-with-HTML-and-CSS/"
date: "2023-09-10"
tags: [Development", "CSS", "Styling", "Coding", "Guide"]
draft: "false"
toc: "true"
---

If you're just starting your journey into web development, you might have heard of a term called "navbar." A navbar, short for navigation bar, is a common element you'll find on almost every website. It's the menu at the top (or sometimes at the side i:e sidebar) of a webpage that helps visitors navigate through different parts of the site. In this beginner-friendly guide, we'll walk you through creating a simple navbar using HTML and CSS.

## HTML - The Structure

First, let's understand the HTML part of creating a navbar.

### 1. `<nav>` Element:

This is the container for your navbar. It helps identify the navigation section of your webpage.

### 2. `<ul>` Element:

Inside the `<nav>`, you'll have an unordered list. `<ul>` stands for an unordered list, and it's used to create the menu items in your navbar.

### 3. `<li>` Element:

Each item in your navbar is created using the list item element, `<li>`. You'll have one `<li>` for each menu option.

### 4. `<a>` Element:

To make these list items clickable links, you'll use the anchor element, `<a>`. This is where you'll specify the text that appears in the navbar and the destination URL.

#### Example:

Here's a simple example of what your HTML structure might look like:

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

<hr>

## CSS - The Styling

Now that we have our basic structure in place, let's make our navbar look good. CSS (Cascading Style Sheets) is the language for styling web pages. Here are some CSS properties you'll use:

### 1. background-color:

Sets the background color of your navbar.

### 2. color:

Sets the text color.

### 3. padding:

Adds space around the content of your navbar.

### 4. text-decoration:

Removes the default underline from links.

### 5. list-style-type:

Removes the bullet points from the list items.

#### Example:

Here's an example of some CSS code to style your navbar:

```css
nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline;
  margin-right: 20px;
}
a {
  color: #fff;
  text-decoration: none;
}
```

<hr>

## Putting It All Together

Now that we understand the structure (HTML) and the style (CSS), let's put it all together. You should have an HTML file where you've defined your navbar structure, and a CSS file where you've added your styles. (Like two separate Files)

- Create an HTML file (e.g., index.html) and add your HTML structure inside the `<body>` tags.
- Create a CSS file (e.g.,styles.css) and link it to your HTML file using the `<link>` element in the `<head>` section of your HTML file. Example:

```html
<head>
  <link rel="stylesheet" type="text/css" href="styles.css(File name)" />
</head>
```

- Open your HTML file in a web browser to see your basic navbar.

<hr>

### Conclusion

Congratulations! You've just created a simple navbar using HTML and CSS. You can further customize and enhance it by adding more styling or functionality as you continue to learn and grow as a web developer. Keep experimenting, and you'll soon be able to create more complex and impressive navigation bars for your websites. Happy coding!

---
