# css-challenge
kabisa css-challenge! 

## 101

There are a good indept article for understanding layout:

* [position](http://alistapart.com/article/css-positioning-101)
* [float](http://alistapart.com/article/css-floats-101)

In the following paragraph, some of the essentials. 

## Floats

Use clear fix solution to make parent div wrap floating child elements

* [Css tricks - clear fix](https://css-tricks.com/snippets/css/clear-fix/)
* `Flexbox` is more modern solution, but not yet supported on all browsers

## Collapsing marging

Normal vertical stacked divs collapse the margin

* [W3C Box model, 8.3.1 Collapsing margins](http://www.w3.org/TR/CSS21/box.html#collapsing-margins")
  

## Aligning elements with same 'column' width

Default behaviour adds `padding` and `border` width to element width.

* box-sizing: border-box; changes this behaviour to make padding and border part of element width.
* Wrapping element: As margin still adds to the width, a wrapping element without any padding, margin and border is the standard solution to solve that
* Be aware when using `inline-block` that space use pixel too 

> '...&lt;/div&gt;&lt;div&gt;...' != '...&lt;/div&gt;  &lt;div&gt;...' 

## Position

Standard position is `static`. To position an child element with `absolut` position within it's parent the parent must have `relative` as position
