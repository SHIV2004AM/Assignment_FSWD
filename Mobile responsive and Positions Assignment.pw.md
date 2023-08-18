1. What is position property in CSS and its type?

answer-> Position Property in CSS and Its Types:
The position property in CSS is used to control the positioning of an element within its containing element. It specifies how an element should be positioned in relation to its normal position in the document flow.
There are four main values for the position property:

Static (Default): Elements with position: static; are positioned according to the normal flow of the document. This is the default behavior for all elements.

Relative: Elements with position: relative; are positioned relative to their normal position in the document flow. You can use top, right, bottom, and left properties to move the element from its original position.

Absolute: Elements with position: absolute; are positioned relative to their closest positioned ancestor (an ancestor with a position other than static) or the containing block if there's no positioned ancestor. They are taken out of the normal document flow, and their position is determined by the specified offsets (top, right, bottom, left).

Fixed: Elements with position: fixed; are positioned relative to the viewport (browser window). They remain in a fixed position even when the page is scrolled.

2. How many types of positioning are there in CSS?

answer-> Types of Positioning in CSS:
There are four types of positioning in CSS, as determined by the position property:
Static: Elements are positioned according to the normal flow of the document and are not affected by top, right, bottom, or left properties.

Relative: Elements are positioned relative to their normal position in the document flow. The top, right, bottom, and left properties can be used to adjust their position.

Absolute: Elements are positioned relative to their closest positioned ancestor or the containing block. They are taken out of the normal flow. The top, right, bottom, and left properties determine their position.

Fixed: Elements are positioned relative to the viewport. They stay in a fixed position even when the page is scrolled. The top, right, bottom, and left properties control their placement.

3. What is Z-index and why to use it?

answer-> Z-index and Its Usage:
The z-index property in CSS controls the stacking order of positioned elements on the z-axis (perpendicular to the screen). It only has an effect on elements with a specified position value other than static (such as relative, absolute, or fixed).
When elements overlap on a web page, the z-index property determines which element appears on top. Elements with a higher z-index value will be positioned above elements with lower values. If multiple elements have the same z-index, the stacking order will be determined by their position in the HTML document.

The z-index property can be both positive and negative. Positive values bring elements closer to the front, while negative values push them further back. For example:
.element1 {
    position: absolute;
    z-index: 2;
}

.element2 {
    position: absolute;
    z-index: 1;
}
In this example, element1 will appear above element2 because it has a higher z-index value.

Using z-index is important when dealing with overlapping elements, such as dropdown menus, modal dialogs, or layered designs, as it helps you control the visual hierarchy of your content.




