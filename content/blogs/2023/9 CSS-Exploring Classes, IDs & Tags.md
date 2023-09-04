---
title: "CSS (Cascading Style Sheets) for Styling HTML: Exploring Classes, IDs, and Tags"
author: "Maheen Waris"
description: ""
url: "/blogs/CSS-for-Styling-HTML-Exploring-Classes-IDs-and-Tags/"
date: "2023-09-09"
tags: [Development", "CSS", "Styling", "Coding"]
draft: "false"
toc: "true"
---

Cascading Style Sheets (CSS) is a fundamental web technology that allows developers to control the visual presentation of HTML documents. With CSS, you can customize the appearance of your web pages, making them more attractive and user-friendly. In this article, we'll delve into three essential ways to apply CSS styling to HTML elements: using classes, IDs, and HTML tags.

## 1. Styling with Classes

CSS classes are reusable styles that you can apply to multiple HTML elements. To create a CSS class, you define a set of style rules in your stylesheet and assign a class name to one or more HTML elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .highlight {
        background-color: yellow;
        color: black;
      }
    </style>
  </head>

  <body>
    <p class="highlight">This paragraph is highlighted.</p>
    <p>This paragraph is not highlighted.</p>
  </body>
</html>
```

#### Example:

In this example, we defined a CSS class called `.highlight` and applied it to the first `<p>` element. As a result, the text within that paragraph is highlighted with a yellow background and black text.

- Using classes allows for efficient and consistent styling across multiple elements with similar characteristics.

<hr>

## 2. Styling with IDs

IDs, like classes, allow you to apply unique styles to specific HTML elements. However, unlike classes, IDs should only be assigned to a single element on a page since they are intended for unique identification.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      #unique-element {
        font-size: 24px;
        color: blue;
      }
    </style>
  </head>
  <body>
    <p id="unique-element">This paragraph has a unique style.</p>
    <p>This paragraph does not have the unique style.</p>
  </body>
</html>
```

#### Example:

In this example, we defined a CSS style for an element with the ID `unique-element`. When this style is applied to the first `<p>` element, it sets a larger font size and changes the text color to blue.

- IDs are useful when you need to apply a distinct style to a single element, such as a header or footer.

<hr>

## 3. Styling with HTML Tags

CSS can also be applied directly to HTML tags. This approach allows you to define styles that are applied to all instances of a specific HTML element.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      p {
        font-family: Arial, sans-serif;
        margin: 10px;
      }
    </style>
  </head>
  <body>
    <p>This is a styled paragraph.</p>
    <p>Another styled paragraph.</p>
  </body>
</html>
```

#### Example:

Here, we've styled all `<p>` elements on the page by specifying the `p` selector. This sets a specific font family and adds a margin of 10 pixels to every paragraph.

- Styling by HTML tags can be an efficient way to establish a consistent look for a group of related elements.

<hr>

### Conclusion

In web development, CSS is a vital tool for enhancing the visual appeal and functionality of HTML documents. By leveraging classes, IDs, and HTML tags, you can control the appearance of your web content with precision and consistency. Whether you need to style multiple elements uniformly or apply unique styles to individual elements, CSS provides the flexibility to make your web pages stand out and engage users effectively.

---
