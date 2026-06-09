# CSS Selectors

## What are CSS Selectors?
CSS selectors are used to select HTML elements that you want to style.

---

# 1. Element Selector

The element selector selects HTML elements by tag name.

## CSS

```css
p {
  color: red;
  text-align: center;
}
```

## HTML

```html
<p>Hello CSS</p>
<p>Welcome Students</p>
```

---

# 2. ID Selector

The ID selector selects one unique element.

## CSS

```css
#title {
  color: blue;
  font-size: 40px;
}
```

## HTML

```html
<h1 id="title">My Website</h1>
```

---

# 3. Class Selector

The class selector styles elements with the same class name.

## CSS

```css
.center {
  text-align: center;
  color: green;
}
```

## HTML

```html
<h2 class="center">Heading</h2>
<p class="center">Paragraph</p>
```

---

# 4. Multiple Classes Example

An element can use more than one class.

## CSS

```css
.center {
  text-align: center;
}

.large {
  font-size: 32px;
}
```

## HTML

```html
<p class="center large">
  Big Center Text
</p>
```

---

# Real-World Example: Online Shop Card

## HTML

```html
<div class="product">
  <h2 class="title">Laptop</h2>
  <p id="price">$999</p>
</div>
```

## CSS

```css
.product {
  border: 1px solid gray;
  padding: 10px;
}

.title {
  color: blue;
}

#price {
  color: green;
  font-size: 24px;
}
```

---

# Quick Summary

| Selector | Symbol | Example |
|---|---|---|
| Element | none | `p` |
| ID | `#` | `#header` |
| Class | `.` | `.menu` |
| Element + Class | `.` | `p.center` |
