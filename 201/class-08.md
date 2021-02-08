[Return to the Table of Contents](README.md)

# Duckett HTML Book
 ## Ch 15 Layout
  ### Key Concepts in Positioning Elements
   #### Building Blocks
   - CSS treats each HTML element as if it is in its own box.
   - This box will either be a block-level box or an inline box.
   #### Containing Elements
   - If one block-level elements sits inside another block-level element then the outer box is known as the `containing` or `parent` element.
   #### Controlling the Position of Elements
   - CSS has the following `positioning schemes` that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning.
   - You specify the positioning scheme using the position property in CSS.
   - You can also float elements using the float property.
   - To indicate where a box should be positioned, you may also need to use `box offset` properties to tell the browser how far from the top or bottom and left or right it should be placed.
   - You will meet these when we introduce the positioning scheme.
   #### Normal Flow (position: static)
   - In normal flow, each block-level element sits on top of the next one.
   - Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: position static;
   #### Relative Positioning (position: relative)
   - Relative positioning moves an element in relation to where it would have been in normal flow.