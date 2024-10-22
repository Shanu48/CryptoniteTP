# Basic HTML

## Getting Started with HTML

To begin writing HTML, you need to understand the basic structure of an HTML document. Here's a simple template:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

- `<!DOCTYPE html>`: This declaration defines the document as an HTML5 document.
- `<html>`: The root element that contains the entire HTML content.
- `<head>`: This section contains meta-information such as the title.
- `<body>`: The section where all visible content is placed.

---

## Headings

Headings help structure your content. HTML provides six levels of headings, from `<h1>` (largest) to `<h6>` (smallest).

```html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
```

---

## Paragraphs

Use the `<p>` tag to create a paragraph of text.

```html
<p>This is a paragraph of text.</p>
```

---

## Formatting Text

You can make text bold or italicized for emphasis using the following tags:
- `<strong>` for bold text.
- `<em>` for italicized text.

```html
<p>This is <strong>bold text</strong> and this is <em>italicized text</em>.</p>
```

---

## Lists

HTML supports ordered (numbered) and unordered (bullet-point) lists:

- **Unordered List**:

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

- **Ordered List**:

```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

---

## Adding Images

To display an image, use the `<img>` tag with the `src` attribute (for the image file path) and `alt` attribute (alternative text for the image):

```html
<img src="image.jpg" alt="Description of the image">
```

---

## Creating Links

To add hyperlinks to your page, use the `<a>` tag with the `href` attribute for the URL:

```html
<a href="https://example.com">Visit Example.com</a>
```
