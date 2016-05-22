#[Learn CSS Layout the pedantic way](http://book.mixu.net/css/index.html)
###1. Box positioning in CSS 

CSS 2.1 defines three positioning schemes, which are:

* normal flow, which consists of three formatting contexts: the block, inline and relative formatting contexts
* floats, which interact with normal flow in their own way and form the basis of most modern CSS grid frameworks
* absolute positioning, which deals with absolute and fixed elements relative to the normal flow

1.1 Anonymous block boxes

In short, when inline-level and block-level boxes are mixed in a single parent element, the inline-level boxes are broken around the block-level box and the inline-level box content is enclosed in an anonymous block-level box.

1.2 Anonymous inline boxes

Anonymous box generation ensures that if any block-level content is mixed in with inline-level siblings, then the inline-level boxes are wrapped in anonymous block-level containers for purposes of layout, which means that they are laid out relative to other boxes as if they were block-level boxes.

1.3 Normal flow: block formatting

The two most important takeaways are that in a box formatting context, boxes are laid out vertically, and that every box's left outer edge will touch the left outer edge of the containing block (even in the presence of floats).

1.4 Normal flow: inline formatting

Line boxes are generated as needed; their width is generally the width of the containing block (minus floats) and their height is always sufficient for all the boxes it contains. In other words, when inline boxes exceed the width of a line box, it will be split if possible. When the rules disallow splitting the box, it will simply horizontally overflow the line box.
