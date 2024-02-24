# Q-1 
## Are the HTML tags and elements the same thing?
### Ans
- No both are different things.
- **HTML Tags:** These are the markers within angle brackets that tell
the browser how to interpret content. An opening tag (e.g., <p>) and
a closing tag (e.g., </p>) usually work together.
- **Example:** `<p>`
- **HTML Elements:** An element is the combination of the opening tag,
any attributes within the opening tag, the content between the tags,
and the closing tag.
**Example:**`<p> this is paragraph</p>`


# Q-2
## What are tags and attributes in HTML?
### Ans 
-Tags: Tags define the structure and meaning of your content **e.g:**,
`<h1>` for a heading, `<p>` for a paragraph).
- Attributes: Attributes provide extra information about the tags. They
come in name-value pairs within the opening tag **e.g:** , `<img
src="myimage.jpg" alt="Description of the image">` has 'src'
and 'alt' attributes)

# Q-3
## What are void elements in HTML? With Example.
### Ans
- Void elements are elements that don't have a closing tag. They
stand alone.
 **Examples:**
 `<br>` (line break)
`<img>` (image)
`<input>` (text field)
 `<hr>` (horizontal line)

# Q-4
## What are HTML Entities? With Example.
### Ans
- HTML Entities are special character codes used to represent
symbols, reserved characters, or characters not on your keyboard in
HTML.
 **Examples:**
`&lt;`&lt; represents the less than symbol (<)
`&gt;`&gt; represents the greater than symbol (>)
` &nbsp;`&nbsp; represents a non-breaking space
` &copy;`&copy; represents the copyright symbol (©)

# Q-5
## What are the different types of lists in HTML? With Example.
### Ans
1. Unordered List (<ul>)
 Creates a bulleted list.
 **Example:**
``` HTML

<ul>
<li>Item 1</li>
<li>Item 2</li>
</ul>
```
2.Ordered List (<ol>)
 Creates a numbered list.
**Example:**

 ```HTML
<ol>
<li>Step 1</li>
<li>Step 2</li>
</ol>
```

# Q-6
## what is the 'class' attribute in HTML? With Example.
### Ans
 The 'class' attribute is used to identify multiple elements that should
share the same styles or behaviors. Styles are defined separately in
CSS.
 **Example:**
 ```HTML
<p class="important">This paragraph is important.</p>
<p class="important">This one too!</p>
```
# Q-7
## what is the difference between the 'id' attribute and the 'class'attribute of HTML elements? With Example.
### Ans
id Must be unique per page 
and
class can be usd on muliple elments.
**example:** id- #id_name
**example:** class- .class_name

# Q-8
## what are the various formatting tags in html?
### Ans
`<b>` Bold text
`<i>` Italicized text
`<u>`Underlined text
`<em>`Emphasized text (usually italicized)
`<strong>` Important text (usually bold)

# Q-9
## How is Cell Padding different from Cell Spacing? With Example.
### Ans
- Cell Padding: Controls the space between
the cell content and the cell border.
 Cell Spacing: Controls the space between the borders of
adjacent cells.
**Example:**

```hTML
<table border="1" cellpadding="10" cellspacing="5">
<tr>
<td>Cell 1</td>
<td>Cell 2</td>
</tr>
</table>
```

cellpadding: Gives 10 pixels of space between content and cell
border.
cellspacing: Gives 5 pixels of space between the borders of
neighboring cells.

# Q-10
## How can we club two or more rows or columns into a single row or column in an HTML table? With Example.
### Ans
Use the following attributes:
rowspan: On a <td> or <th> element, to make a cell span multiple
rows.
colspan: On a <td> or <th> element, to make a cell span multiple
columns.
**Example:** (combining two columns):
```HTML
<table>
<tr>
<td colspan="2">This cell spans two columns</td>
</tr>
<tr>
<td>Normal cell</td>
<td>Normal cell</td>
</tr>
</table>
```
# Q-11
## What is the difference between a block-level element and an inline element?
### Ans
- Block-level elements:
Always start on a new line.
Take up the full width available to them.
 Have a top and bottom margin.
 ```html

  **Examples:** <div>, <p>, <h1>, <section>, <article>

 Inline elements:
 Don't start on a new line.
 Take up only the necessary width.
 Don't have top and bottom margins (though they can have
side margins)

 **Examples:** <span>, <strong>, <a>, <img>
 ```

# Q-12
## How to create a Hyperlink in HTML? With Example.
### Ans 
Use the `<a>` tag (anchor tag):
```HTML
<a href="https://www.example.com">Click here to visit Example
Website</a>
 href: The URL the link points to.
 Text between <a> and </a>: The clickable text displayed to the
user.
```
# Q-13
## What is the use of an iframe tag? With Example.
### Ans

- An `<iframe>` embeds another HTML document within your
current document.
Use Cases:
Displaying external content (e.g., a YouTube video)
Creating isolated sections within a page.
**example:**
```HTML
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"
width="560" height="315"></iframe>
```

# Q-14
## what is the use of a span tag? Explain with example?
# Ans

`<span>` is a generic inline container. It doesn't have any inherent
meaning on its own.
 Uses:
 Applying styles to a segment of text within another
element (e.g a paragraph)
 Grouping small sections of inline content for scripting
purposes.

**Example:**

```HTML
<p>This is a paragraph with a <span style="color:
red;">highlighted word</span>.</p>
```

# Q-15
## How to insert a picture into a background image of a web page? With example.
###
```HTML
<div class="background-image"></div>
<style>
.background-image {
background-image: url("your_background_image.jpg");
width: 500px;
height: 300px;
background-repeat: no-repeat; /* Prevents background image
from repeating */
background-size: cover; /* Ensures background image
covers the whole area */
}
</style>
```
# Q-16
## what are the different tags to separate sections of text?
### Ans
`<br>` tag - it is use to separate the line of text.
`<p>` tag- it is used to write a paragraph o text.


# Q-17
## How are active links different from normal links?
### Ans
Active links usually visually change when the user interacts with
them. Common states in CSS, often controlled with the :active
pseudo-class:
 Normal: Default appearance
 Visited: Style if the user has already clicked the link

# Q-18
## what is SVG
### Ans
SVG stands for Scalable Vector Graphics.
 It's an XML-based format for defining vector images. Unlike
raster images (JPG, PNG), SVG images remain crisp at any size
because they're defined by mathematical shapes and paths
rather than pixels.
 

 # Q-19
 ## What is the difference between HTML and XHTML?
 ### Ans
 - hTML (Hypertext Markup Language):
 Standard foundation for webpages
 More forgiving in terms of syntax (e.g., you can sometimes
forget to close tags)
- XHTML (Extensible Hypertext Markup Language):
 A stricter version of HTML that adheres to XML rules.All tags must be closed, attributes must be in lowercase,
etc.
 XHTML is less commonly used today in favour of html5.

 # Q-20
 ## Logical and Physical Tags in HTML
 ### Ans
 - ogical Tags: Describe the meaning or purpose of the content.
 Examples: `<em>` (emphasis), `<strong>` (important text), `<h1>`
- `<h6>` (headings)
 Physical Tags: Describe how the content should be formatted
visually.
 **Examples:** `<b>` (bold), `<i>` (italic), `<u>` (underline)
 




