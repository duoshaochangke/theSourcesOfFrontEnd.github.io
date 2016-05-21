#Perfect Article:
###1.How to center?
* 1.1[Absolute Centering in CSS](http://codepen.io/shshaw/full/gEiDt)
* 1.2[How To Center Anything With CSS](https://codemyviews.com/blog/how-to-center-anything-with-css#comment-684580538)
      * Horizontally Center an Element
         * the width must always be set.
         * this trick will work on most block level elements.
      * Center An Absolutely Positioned Element
         * left = \(x - y\) / 2, x=parentWidth, y=childWidth.
      * With Fluid Width
         * left = 50%; margin: 0 0 0 -\(x/2\); x=childWidth.
      * Dead Center an Element
         * left = 50%; margin: -\(y/2\) 0 0 -\(x/2\); x=childWidth, y=childHeight.
      * Centering a Background Image
         * background: center;
         
___?: The theory of negative margin ?___
         
###2.Navigation
* 2.1[Subtle and modern effects for links or menu items](http://tympanus.net/Development/CreativeLinkEffects/)

###3.Layout
* 3.1[Learn CSS Layout](http://learnlayout.com/)

###4.Position
w3.org:[CSS Positioned Layout Module Level 3](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

   MDN:[Position](https://developer.mozilla.org/en-US/docs/Web/CSS/position) 
* 4.1[The Lowdown On Absolute vs. Relative Positioning](https://codemyviews.com/blog/the-lowdown-on-absolute-vs-relative-positioning)
  * The first is that *relative* positioning will allow you to tweak an element’s position relative to its normal starting point.
  * The second is that *absolute* positioning will allow you to tweak an element’s position relative to its first non-statically-positioned ancestor (defaults to page bounds if none is found). 
  * The final piece of information to remember is that both relatively and absolutely positioned items won’t affect the static and fixed items around them (**absolutely positioned items are _removed from the flow_, relatively positioned items occupy their _original position_**).
