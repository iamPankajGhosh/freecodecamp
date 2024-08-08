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

# Step 10

You can link to another page with the anchor (`a`) element.

Here is an example linking to `https://google.com`

```
<a href="https://google.com"></a>
```

# Step 11

A link's text must be placed between the opening and closing tags of an anchor (`a`) element.

Here is an example of a link with the text click here to go to `google.com`:

```
<a href="https://www.google.com">click here to go to google.com</a>
```

# Step 12

You can turn any text into a link, such as the text inside of a `p` element.

Example Code

```
<p>I think <a href="https://www.google.com">Google</a> is great.</p>
```

# Step 13

To open links in a new tab, you can use the `target` attribute on the anchor (`a`) element.

The `target` attribute specifies where to open the linked document. `target="_blank"` opens the linked document in a new tab or window.

Here is the basic syntax for an `a` element with a `target` attribute:

```
<a href="https://www.google.com" target="_blank">Google</a>
```

# Step 14

In previous steps you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.

Here is an example of turning an image into a link:

```
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
```

# Step 15

Before adding any new content, you should make use of a `section` element to separate the cat photos content from the future content.

The `section` element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.

Example Code

```
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
```

# Step 16

To create an unordered list of items, you can use the `ul` element.

The `li` element is used to create a list item in an ordered or unordered list.

Example Code

```
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```

# Step 17

The `figure` element represents self-contained content and will allow you to associate an image with a caption.

Nest the image you just added within a figure element.

# Step 18

A figure caption (`figcaption`) element is used to add a caption to describe the image contained within the `figure` element.

Here is an example of a `figcaption` element with the caption of `A cute cat`:

```
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```

# Step 19

To place emphasis on a specific word or phrase, you can use the `em` element.

Example Code

```
<figcaption>Cats <em>love</em> lasagna.</figcaption>
```

# Step 20

The code for an ordered list (`ol`) is similar to an unordered list, but list items in an ordered list are numbered when displayed.

Example Code

```
<ol>
  <li>thunder</li>
  <li>other cats</li>
</ol>
```

# Step 21

The `strong` element is used to indicate that some text is of strong importance or urgent.

Example Code

```
<figcaption>Cats <strong>hate</strong> other cats.</figcaption>
```

# Step 22

The `form` element is used to get information from a user like their name, email, and other details.

The `action` attribute indicates where form data should be sent.

Here is an example of a `form` element with an `action` attribute:

```
<form action="/submit-url"></form>
```

# step 23

The `input` element allows you several ways to collect data from a web form. Like img elements, input elements are a void element and do not need closing tags.

There are many kinds of inputs you can create using the `type` attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.

In order for a form's data to be accessed by the location specified in the `action` attribute, you must give the text field a `name` attribute and assign it a value to represent the data being submitted.

A `placeholder` attribute is used to give people a hint about what kind of information to enter into an input.

To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element. There's no need to set a value to the required attribute. Instead, just add the word required to the input element, making sure there is space between it and other attributes.

Example Code

```
<input type="text" name="name" placeholder="Ex. Jane Doe">
```

# Step 24

The `button` element is used to create a clickable button.

Add a `button` element with the text `Submit` below the `input` element. The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's `action` attribute.

Even though you added your button below the text input, they appear next to each other on the page. That's because both `input` and `button` elements are inline elements, which don't appear on new lines.

The button you added will submit the form by default. However, relying on default behavior may cause confusion. Add the `type` attribute with the value `submit` to the `button` to make it clear that it is a submit button.

Example Code

```
<form action="/submit-url">
  <input type="text" name="name" placeholder="Ex. Jane Doe">
  <button type="submit">Submit</button>
</form>
```

# Step 25

You can use radio buttons for questions where you want only one answer out of multiple options.

Here is an example of a radio button with the option of cat:

```
<input type="radio"> cat
```

# Step 26

`label` elements are used to help associate the text for an `input` element with the `input` element itself (especially for assistive technologies like screen readers).

The `id` attribute is used to identify specific HTML elements. Each `id` attribute's value must be unique from all other `id` values for the entire page.

Example Code

```
<label>
  <input id="indoor" type="radio"> Indoor
</label>

<label>
  <input id="outdoor" type="radio"> Outdoor
</label>
```

Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a `name` attribute with the same value.

```
<label>
  <input id="indoor" type="radio" name="indoor-outdoor"> Indoor
</label>

<label>
  <input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor
</label>
```

If you select the `Indoor` radio button and submit the form, the form data for the button is based on its `name` and `value` attributes. Since your radio buttons do not have a `value` attribute, the form data will include `indoor-outdoor=on`, which is not useful when you have multiple buttons.

Add a value attribute to both radio buttons. For convenience, set the button's value attribute to the same value as its `id` attribute.

```
<label>
  <input type="radio" id="indoor" name="indoor-outdoor" value="indoor">
  Indoor
</label>

<label>
  <input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor">
  Outdoor
</label>
```

# Step 27

The `fieldset` element is used to group related inputs and labels together in a web form. `fieldset` elements are block-level elements, meaning that they appear on a new line.

Nest the `Indoor` and `Outdoor` radio buttons within a `fieldset` element, and don't forget to indent the radio buttons.

Example Code

```
<fieldset>
  <label>
    <input id="indoor" type="radio" name="indoor-outdoor" value="indoor">
    Indoor
  </label>

  <label>
    <input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor">
    Outdoor
  </label>
</fieldset>
```

# Step 28

The `legend` element acts as a caption for the content in the `fieldset` element. It gives users context about what they should enter into that part of the form.

Example Code

```
<fieldset>
  <legend>
    Is your cat an indoor or outdoor cat?
  </legend>

  <label>
    <input id="indoor" type="radio" name="indoor-outdoor" value="indoor">
    Indoor
  </label>

  <label>
    <input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor">
    Outdoor
  </label>
</fieldset>
```

# Step 25

Forms commonly use checkboxes for questions that may have more than one answer. The `input` element with a `type` attribute set to `checkbox` creates a checkbox.

Example Code

```
<input type="checkbox" id="loving"> Loving
```

There's another way to associate an `input` element's text with the element itself. You can nest the text within a `label` element and add a `for` attribute with the same value as the `input` element's `id` attribute.

Example Code

```
<input id="loving" type="checkbox">
<label for="loving">Loving</label>
```
