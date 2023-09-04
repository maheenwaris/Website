---
title: "A Beginner's Guide to (CSS) Cascading Style Sheets: Styling Your Web Pages"
author: "Maheen Waris"
description: ""
url: "/blogs/Beginner's-Guide-to-CSS/"
date: "2023-09-08"
tags: [Development", "CSS", "Styling", "Coding", "Guide"]
draft: "false"
toc: "true"
---

## Introduction:

In web development, CSS is like a hidden hero that makes websites look great. In this article, we will explain what CSS is and show you different ways it's used with examples.

## What Is CSS?

CSS (Cascading Style Sheets) is a special language used in web development. It's like a set of rules that tell a webpage how to look. It separates how a webpage looks from what's on the webpage (like text and images).
CSS works in a way where you can have many rules for one thing on a webpage, but some rules are more important than others. This helps developers control how a webpage looks.

<hr>

## Varieties of CSS:

There are three main types of CSS:

### 1. Inline CSS:

Inline CSS is directly inserted within an HTML tag, employing the "style" attribute. This type of CSS, known as inline CSS, is the most specific, which means it takes priority over other CSS rules. While it can be useful for quick style changes, many developers frown upon it because it's not easy to maintain. Example:

```html
<p style="color: blue; font-size: 18px;">This is some text.</p>
```

### 2. Internal CSS:

Internal CSS is placed inside the `<style>` tag in the `<head>` section of an HTML document. It affects the style of the whole page, making things more organized compared to inline CSS. However, it's not as flexible as external CSS, which provides even more organization and reusability.
Example:

```html
<head>
  <style>
    p {
      color: red;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <p>This is some text.</p>
</body>
```

### 3. External CSS:

External CSS is like a separate set of style instructions saved in ".css" files. To use it, you link these files to your HTML using the `<link>` tag. This makes your code clean and organized, making it easier to maintain and ensuring that your web pages have a consistent look across all of them.
Example:

```html
<head>
  <link rel="stylesheet" type="text/css" href="styles.css" />
</head>
<body>
  <p>This is some text.</p>
</body>
```

<hr>

### Conclusion:

Cascading Style Sheets (CSS) are like essential tools for web developers. They help separate the content from how it looks, and they offer endless ways to make things look great. Whether you're just starting out or you're a pro, learning CSS lets you create web experiences that are not just eye-catching but also work well on different devices. So, dive into CSS, and show off your creativity on the web!

---
