# CSS Universal Selector and Grouping Selector

---

# CSS Universal Selector (`*`)

The universal selector selects **all HTML elements** on the page.

## Syntax

```css
* {
  property: value;
}
```

## Example

```css
* {
  text-align: center;
  color: blue;
}
```

## Explanation

This CSS rule affects every HTML element on the page.

Examples:

- `<h1>`
- `<p>`
- `<div>`
- `<span>`

All text becomes:

- Center aligned
- Blue colored

---

# CSS Grouping Selector

The grouping selector is used to apply the same styles to multiple elements.

Instead of repeating CSS code, selectors can be grouped using commas.

## Without Grouping

```css
h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
```

---

## With Grouping

```css
h1,
h2,
p {
  text-align: center;
  color: red;
}
```

## Benefits

- Cleaner code
- Less repetition
- Easier maintenance

---

# All CSS Simple Selectors

| Selector           | Example      | Description                               |
| ------------------ | ------------ | ----------------------------------------- |
| `#id`              | `#firstname` | Selects the element with `id="firstname"` |
| `.class`           | `.intro`     | Selects all elements with `class="intro"` |
| `*`                | `*`          | Selects all elements                      |
| `element`          | `p`          | Selects all `<p>` elements                |
| `element, element` | `div, p`     | Selects all `<div>` and `<p>` elements    |

---

# Quick Summary

- Use `*` to style every element on the page.
- Use grouping selectors `,` to apply styles to multiple selectors.
- Simple selectors are the foundation of CSS.
