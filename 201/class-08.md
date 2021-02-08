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
   #### Absolute Positioning (position: absolute)
   - When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.
   - They act like it is not there.
   #### Fixed Positioning (position: fixed)
   - Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.
   #### Overlapping Elements (z-index)
   - When you use relative, flixed, or absolute positioning, boxes can overlap.
   #### Floating Element (float)
   - The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
   #### Using Float to Place Elements Side-by-Side
   - A lot of layouts place boxes next to each other.
   - The float property is commonly used to achieve this.
   #### Clearing Floats (clear)
   - The clear property allows you to say that no element (within the same containing element) should touch the left or right-hand sides of a box.
   - It can take the following values:
    1. Left
    2. Right
    3. Both
    4. None
   #### Parents of Floated Elements: Problem
   - If a containing element `only` contains floated elements, some browsers will treat it as if it is zero pixels tall.
   #### Parents of Floated Elements: Solution
   - Traditionally, developers got around this problem by adding an extra element after the last floated box (inside the containing element).
   - A CSS rule would be applied to this additional element setting the `clear property` to hvae a value of `both`.
   - But this meant that an extra element was added to the HTML just to fix the height of the containing element.
   #### Creating Multi-Column Layouts with Floats
   - Many web pages use multiple columns in their design.
   - This is achieved by using a `<div>` element to represent each column.
   - The following three CSS properties are used to position the columns next to each other:
    1. Width
    2. Float
    3. Margin
   #### Screen Sizes
   - Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
   #### Screen Resolution
   - Resolution refers to the number of dots a screen shows per inch.
   - Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.
   #### Page Sizes
   - Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide.
   - Since most users will be able to see designs this wide on their screens.