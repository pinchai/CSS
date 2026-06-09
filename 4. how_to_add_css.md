# How To Add CSS

When a web browser reads a CSS style sheet, it formats the HTML document according to the CSS rules.

There are **3 ways** to add CSS to HTML:

1. **External CSS** – link to a separate `.css` file  
2. **Internal CSS** – use the `<style>` tag inside the `<head>` section  
3. **Inline CSS** – use the `style` attribute directly on an HTML element  

---

# 1. External CSS

External CSS is stored in a separate `.css` file.

It is the **best method** for large websites because one CSS file can style many pages.

## Example

### HTML File

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>Hello World</h1>
<p>This is external CSS.</p>

</body>
</html>
```

### CSS File (style.css)

```css
body {
    background-color: lightblue;
}

h1 {
    color: navy;
}

p {
    color: darkred;
}
```

---

## Visual Structure

```text
index.html
style.css
```

---

## Advantages

- Easy to manage
- Reusable across multiple pages
- Cleaner HTML code

---

# 2. Internal CSS

Internal CSS uses the `<style>` tag inside the `<head>` section.

## Example

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: lightyellow;
        }

        h1 {
            color: green;
        }

        p {
            color: blue;
        }
    </style>
</head>
<body>

<h1>Hello World</h1>
<p>This is internal CSS.</p>

</body>
</html>
```

---

## Advantages

- Useful for single-page styling
- No separate CSS file needed

---

# 3. Inline CSS

Inline CSS uses the `style` attribute directly inside an HTML element.

## Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="color:red;">Hello World</h1>

<p style="color:blue; font-size:20px;">
    This is inline CSS.
</p>

</body>
</html>
```

---

## Advantages

- Quick styling for a single element

## Disadvantages

- Hard to manage
- Repeats code
- Not recommended for large projects

---

# Comparison Table

| Method | Location | Best Use |
|---|---|---|
| External CSS | Separate `.css` file | Large websites |
| Internal CSS | `<style>` inside `<head>` | Single page |
| Inline CSS | `style=""` attribute | Small quick changes |

---

# Simple Visual Diagram

```text
External CSS
HTML  ------>  style.css

Internal CSS
HTML  ------>  <style> ... </style>

Inline CSS
HTML Element ------> style=""
```

---

# Recommended Practice

✅ Use **External CSS** for most projects.  
✅ Use **Internal CSS** for small single-page examples.  
⚠️ Use **Inline CSS** only for quick testing or special cases.
