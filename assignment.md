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
- there are 2 types of lists in html,which we can see here:-

1. Unordered List (`<ul>`)
- unordered lists, which have no inherent order and each item is bulleted.
 **Example:**
 - phone
 - laptop
 - washing machine
 - fridge

2.Ordered List (`<ol>`)
- ordred lists, which havee an inherent order and each item is numbered.
 Creates a numbered list.
**Example:**
- one
- two
- three
- four

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
**id:**-
- id Must be unique per page.
- it identifying a single element.
- to manipulate a specific element.
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Example</title>
        <style>
            BODY {
                background-color: lightgreen;
            }

            .box {
                background-color: red;
                height: 50px;
                width: 50px;
            }
            #container{
                background-color: orange;
                height: 50px;
                width: 50px;
            }
        </style>
    </head>
    <body>

    Example of id attribute.

        <div id="container"></div>
        its div get css by 'container' id name.

**class:**-
- class can be usd on muliple elments.
- grouping elements for styling or behavior.
- to manipulate a group of elements.
**example:** id- #id_name
**example:** class- .class_name

Example of class attribute.

        <div class="box"></div><br>
        <div class="box"></div><br>
        <div class="box"></div><br>
        its div get css by 'box' class.
    </body>
</html>
```

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
```html
<tr>
        <th style="background-color: rgb(211, 200, 183);">&lt; section &gt;</th>
        <th rowspan="3" style="background-color: dimgrey;">&lt; aside &gt;</th>
      </tr>

      <tr>
        <th style="background-color: rgb(204, 131, 79);">Heading</th>
      </tr>

      <tr style="height: 110PX;">
        <th style="background-color: rgb(136, 107, 163);">&lt; article &gt;</th>
      </tr>

      <tr style="height: 40PX;">
        <th colspan="2" style="background-color: burlywood;">
        &lt; footer &gt;
        </th>
      </tr> 
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
    o insert a picture in background image of a web page we can use background attribute in body tag.
    Example :-

 ```html
   <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Example</title>
  </head>

  <body
    background="https://www.listbark.com/wp-content/uploads/2020/06/Funny-Cricket-Meme-Umpire-Y-You-No-Give-Out-Image.jpg"
    style="background-repeat: no-repeat"
  ></body>
</html>
```
# Q-16
## what are the different tags to separate sections of text?
### Ans
`<br>` tag - it is use to separate the line of text.
`<p>` tag- it is used to write a paragraph o text.
`<section>` tag- it is used to group together related elements.
`<div>` tag- it is used to difines a division or a section in an html document.
`article` tag - it is used to specifies self contained content.

   



# Q-17
## How are active links different from normal links?
### Ans
Active links usually visually change when the user interacts with
them. Common states in CSS, often controlled with the :active
pseudo-class:
 Normal: Default appearance
 Visited: Style if the user has already clicked the link
 - An active link is active till the point of time you click on it and normal link is just created by anchor tag and not clicked.


- In browser by default Active link is underlined and red in color . Visited link is underlined and purple in color 

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
 




