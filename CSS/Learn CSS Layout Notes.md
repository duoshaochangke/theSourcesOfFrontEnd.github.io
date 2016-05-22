#[Learn CSS Layout the pedantic way](http://book.mixu.net/css/index.html)
###1. Box positioning in CSS 

CSS 2.1 defines three positioning schemes, which are:

* normal flow, which consists of three formatting contexts: the block, inline and relative formatting contexts
* floats, which interact with normal flow in their own way and form the basis of most modern CSS grid frameworks
* absolute positioning, which deals with absolute and fixed elements relative to the normal flow

1.1 Anonymous block boxes

In short, when inline-level and block-level boxes are mixed in a single parent element, the inline-level boxes are broken around the block-level box and the inline-level box content is enclosed in an anonymous block-level box.
