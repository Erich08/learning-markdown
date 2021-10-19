# Layout

> CSS treats each HTML as if it is in its own box. This box with either be a **block-level** box or an **inline** box.

Block-level boxes start on a new line and acat as the main buulding blocks of any layour, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

Examples of block-level elements :

- `<h1>`
- `<p>`
- `<ul>`
- `<li>`

Examples of inline elements:

- `<img>`
- `<b>`
- `<i>`

## Containing elements

> If one block-level element sits inside another block-level element then the outer box is known as the _containing_ or _parent_ element.

> It is common to group a number of elements together inside of a `<div>` (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the log and the main navigation). The `<div>` element that contains this group of elements is then referred to as the _containing element_.

Some of examples of controlling the position of elements are:

- Normal flow
  - Every block-level element appears on a new line, causing each item to appear lower down than the previous one.
- Relative positioning
  - This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would habve been placed.
- Absolute positioning
  - This positions the element in relation to its containing element.
- Fixed positioning
  - This is a form of absolute positioning that positions the element in relation to the browser window as opposed to the containing element.
- Floating elements
  - Floating an element allows you to take that element out of the normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.
