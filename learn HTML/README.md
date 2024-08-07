# Step 1

HTML elements have an opening and closing tag with content between.

Here is the basic syntax:

```
<openingTag>content</openingTag>
```

The first element you will learn about is the `h1` element. The `h1` element is a heading and is used for the main heading of a webpage.

```
<h1>This is a main heading</h1>
```

# Step 2

The `h1` through `h6` heading elements are used to signify the importance of content below them. The lower the number, the higher the importance so, `h2` elements have less importance than `h1` elements.

```
<h1>most important heading element</h1>
<h2>second most important heading element</h2>
<h3>third most important heading element</h3>
<h4>fourth most important heading element</h4>
<h5>fifth most important heading element</h5>
<h6>least most important heading element</h6>
```

Only use one `h1` element per page and place lower importance headings below higher importance headings.

# Step 3

The `p` element is used to create a paragraph of text on websites.

```
<p>This is a paragraph</p>
```

# Step 4

Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts with `<!--`, contains any number of lines of text, and ends with `-->`

Here is an example of a comment with the `TODO: Remove h1`

```
<!-- TODO: Remove h1 -->
```

# Step 5

HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with search Engine optimization (SEO) and accessibility.

The `main` element is used to represent the main content of the body of an HTML document. Content inside the `main` element should be unique to the document and should not be repeated in other parts of the document.

Example Code

```
<main>
    <h1>Most important content of the document</h1>
    <p>Some more important content...</p>
</main>
```

# Step 6

In the previous step, you put the `h1` and `p` elements inside the `main` element. This is called nesting. Nested elements should be placed two spaces
further to the right of the element they are nested in. This spaceing is called indentation and it is used to make HTML easier to read.

# Step 7

You can add images to your website by using the `img` element. `img` elements have an opening tag without a closing tag. An element without a closing
tag is known as a void element.

# Step 8

HTML attribute are special words used inside the opening tag of an element to control the element's behaviour. The `src` attribute in an `img` element specifies the image's URL (where the image is located).

Here is an example of an `img` element with a `src` attribute pointing to the demo image

```
<img src="https://cdn.demo.com/images/demo.svg">
```

# Step 9

All `img` elements should have an `alt` attribute. The `alt` attribute's text is used for screen readers to improve accessibility and is diplayed if the image failed to load.

Example code

```
<img src="cat.jpg" alt="A cat">
```
