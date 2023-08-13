1. What is padding and margin and when do you use them?

answer-> Padding and Margin:

Padding: Padding is the space between the content of an element and its border. It provides inner spacing within an element. Padding can be set on all sides (top, right, bottom, and left) individually or collectively.

Margin: Margin is the space outside the border of an element. It provides spacing between elements. Like padding, margins can also be set on all sides or individually.
When to use them:

Padding: Use padding to create space between the content and the border of an element, ensuring that the content doesn't touch the border directly.
Margin: Use margin to control the spacing between elements on a webpage, creating visual separation between them.

2. What is display property and explain display inline, block, and inline-block?

answer-> Display Property and Values:
The display property in CSS determines how an element is rendered in the layout.

display: inline;: Elements with display: inline; are rendered as inline elements. They flow within the text content and only take up as much width as necessary. Examples include <span>, <a>, and <em> elements.
display: block;: Elements with display: block; are rendered as block-level elements. They take up the full available width by default and create a new line before and after the element. Examples include <div>, <p>, and <h1> to <h6> elements.
display: inline-block;: Elements with display: inline-block; are a combination of inline and block elements. They flow inline like text, but you can apply width, height, padding, and margin to them. This is useful for creating elements that have both inline behavior and can hold block-level styling.

3. Explain min-height, min-width, max-height, and max-width in CSS?

answer-> min-height, min-width, max-height, and max-width:

min-height: Sets the minimum height an element can be. If the content inside the element requires more space, the element will expand beyond the minimum height.
min-width: Sets the minimum width an element can be. If the content inside the element requires more space, the element will expand beyond the minimum width.
max-height: Sets the maximum height an element can be. If the content inside the element exceeds the specified maximum height, it will be clipped or overflowed.
max-width: Sets the maximum width an element can be. If the content inside the element exceeds the specified maximum width, it will be clipped or overflowed.
These properties are particularly useful when you want to ensure that an element doesn't become too small or too large, while still allowing it to expand or contract based on its content and available space.