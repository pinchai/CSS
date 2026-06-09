# CSS Syntax

A CSS rule consists of:

1. **Selector**
2. **Declaration Block**

---

## CSS Syntax Diagram

![CSS Syntax Diagram](image.png)

---

# Example

```css
h1 {
  color: blue;
  font-size: 12px;
}
```

---

# Example Explained

| Part        | Description |
| ----------- | ----------- |
| `h1`        | Selector    |
| `color`     | Property    |
| `blue`      | Value       |
| `font-size` | Property    |
| `12px`      | Value       |

---

# Structure Breakdown

```css
selector {
  property: value;
}
```

---

# Real HTML + CSS Example

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      h1 {
        color: blue;
        font-size: 12px;
      }
    </style>
  </head>
  <body>
    <h1>Hello CSS</h1>
  </body>
</html>
```

---

# Output Result

- The heading text becomes **blue**
- The font size becomes **12px**

---

# Important Symbols in CSS

| Symbol | Meaning                      |
| ------ | ---------------------------- |
| `{ }`  | Declaration block            |
| `:`    | Separates property and value |
| `;`    | Separates declarations       |

---

# Quick Summary

| Part              | Description                       |
| ----------------- | --------------------------------- |
| Selector          | Selects HTML elements             |
| Property          | What to style                     |
| Value             | Style setting                     |
| Declaration       | Property + value                  |
| Declaration Block | Group of declarations inside `{}` |
