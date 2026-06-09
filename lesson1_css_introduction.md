# CSS Introduction

## What is CSS?

**CSS** stands for **Cascading Style Sheets**.

CSS is used to style and design web pages. It controls how HTML elements look on the screen.

With CSS, you can change:

- Colors
- Fonts
- Sizes
- Layouts
- Spacing
- Animations

HTML creates the structure of a webpage, while CSS makes it beautiful.

---

# CSS Demo - One HTML Page - Multiple Styles!

The same HTML page can look completely different by changing only the CSS file.

## Example

### HTML File

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a simple paragraph.</p>
  </body>
</html>
```

---

## Style 1

```css
body {
  background-color: white;
  color: black;
  font-family: Arial;
}
```

Result:

- White background
- Black text
- Simple design

---

## Style 2

```css
body {
  background-color: black;
  color: yellow;
  font-family: Courier New;
}
```

Result:

- Dark background
- Yellow text
- Hacker-style appearance

---

## Style 3

```css
body {
  background: linear-gradient(to right, blue, purple);
  color: white;
  text-align: center;
}
```

Result:

- Gradient background
- Modern colorful design
- Centered text

---

# Why Use CSS?

CSS is important because it helps developers:

## 1. Make Websites Beautiful

CSS adds colors, layouts, fonts, and animations.

Without CSS, websites look plain and boring.

---

## 2. Separate Design from Content

HTML handles content.

CSS handles design.

This makes code cleaner and easier to manage.

---

## 3. Improve User Experience

Good design makes websites:

- Easier to read
- Easier to navigate
- More attractive

---

## 4. Create Responsive Design

CSS helps websites work on:

- Phones
- Tablets
- Laptops
- Large screens

Example:

```css
@media screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
```

---

# CSS Saves a Lot of Work!

One CSS file can style many HTML pages at the same time.

Instead of styling each page separately, developers write CSS once and reuse it everywhere.

## Example

### External CSS File

```css
h1 {
  color: blue;
}

p {
  font-size: 18px;
}
```

This style can automatically apply to:

- Home page
- About page
- Contact page
- Product page

---

# Real-World Example

Imagine a school website with 100 pages.

Without CSS:

- You must manually style every page.

With CSS:

- Change one CSS file → all 100 pages update instantly.

Example:

```css
body {
  font-family: Arial;
}
```

All pages will immediately use the new font.

---

# Summary

| Topic        | Description                       |
| ------------ | --------------------------------- |
| CSS          | Styles web pages                  |
| HTML         | Creates webpage structure         |
| Main Benefit | Beautiful and organized design    |
| Reusable     | One CSS file can style many pages |
| Responsive   | Works on different screen sizes   |

---

# Lesson 1: Exercises

## Exercise 1: Understanding CSS Basics
1. What does **CSS** stand for?
2. What is the main difference between HTML and CSS in web development?
3. Name at least three things that CSS can change on a web page.

## Exercise 2: Why Use CSS?
1. Why is it beneficial to separate design (CSS) from content (HTML)?
2. How does CSS save a lot of work when building a large website? (Hint: Think about styling multiple pages).
3. What is "Responsive Design" and why is it important?

## Exercise 3: Code Analysis
Look at the following CSS code:
```css
body {
    background-color: lightblue;
    color: darkblue;
    font-family: Arial;
}
```
1. What HTML element is this CSS styling?
2. What will the background color of the page be?
3. What color will the text be?

## Exercise 4: Practical Task
Create a simple HTML file with a heading (`<h1>`) and a paragraph (`<p>`). Then, add an internal CSS style (inside the `<style>` tag in the `<head>`) to:
1. Make the background color of the page light gray.
2. Make the heading text green and centered.
3. Make the paragraph text italic and 18px in size.
