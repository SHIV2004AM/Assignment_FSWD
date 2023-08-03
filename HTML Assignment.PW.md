1. What are inline and block elements in HTML and the difference between them? Name a few inline

answer-> Inline and Block Elements in HTML:
Inline elements and block elements are two types of HTML elements that behave differently when rendered on a web page.

Inline Elements:

Inline elements are elements that only take up as much width as necessary to fit their content, and they do not start on a new line.
They allow other elements to be displayed to their left and right.
Common inline elements include <span>, <a>, <strong>, <em>, <img>, <input>, <label>, <br>, etc.
Block Elements:

Block elements are elements that take up the full available width of their container and always start on a new line.
They create a "block" of content, and other elements are displayed below them.
Common block elements include <div>, <p>, <h1>, <ul>, <li>, <table>, <form>, <header>, <footer>, etc.
Difference between Inline and Block Elements:

Inline elements do not create line breaks, while block elements always start on a new line.
Inline elements only take up the width of their content, while block elements occupy the full available width of their container.
Inline elements can have other inline elements next to them, whereas block elements are usually stacked on top of each other.

2. How to work with images in HTML and explain in detail ‹img /> tag important attributes.

answer-> Working with Images in HTML:
To add images to an HTML page, you use the <img> tag. Here's how you do it:
<img src="image.jpg" alt="Image Description" width="300px" height="200px" />
Explanation of Important Attributes:

src: This attribute specifies the URL or file path of the image. It is required for the <img> tag to work. For example, src="image.jpg" indicates the image file is named "image.jpg" and located in the same directory as the HTML file.

alt: The "alt" attribute provides alternative text for the image. It is displayed if the image cannot be loaded or for users who use screen readers. Always include meaningful alternative text for accessibility purposes. For example, alt="A beautiful landscape".

width and height: These attributes specify the width and height of the image in pixels. It's a good practice to set these attributes to the actual dimensions of the image. If these attributes are not specified, the image will be displayed at its original size. For example, width="300px" height="200px".

3. How to create lists in HTML?

answer-> Creating Lists in HTML:
There are three types of lists in HTML:

a. Unordered List (ul):
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

b. Ordered List (ol):
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
  </ol>

  c. Definition List (dl):
  <dl>
    <dt>Term 1</dt>
    <dd>Definition 1</dd>
    <dt>Term 2</dt>
    <dd>Definition 2</dd>
  </dl>
  
4. How to interlink web pages and navigate people to other websites?

answer-> Interlinking Web Pages and Navigating to Other Websites:
To create links that interlink your web pages or lead to external websites, you use the <a> (anchor) tag. Here's how:

a. Link to Another Page in the Same Website:
<a href="page.html">Link Text</a>

b. Link to a Specific Section/ID in the Same Page:
<a href="#section-id">Link Text</a>

c. Link to an External Website:
<a href="https://www.example.com">Link Text</a>

The href attribute specifies the URL the link points to. For internal links, use the relative path, and for external links, use the full URL.

Remember to replace "page.html" with the actual filename or path of the target page and "section-id" with the ID of the section you want to link to within the same page.

By using the <a> tag, you can create hyperlinks that allow users to navigate between your web pages and other websites.

