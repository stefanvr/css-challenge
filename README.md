# css-challenge
kabisa css-challenge

## Floats

Use clear fix solution to make parent div wrap floating child elements

* https://css-tricks.com/snippets/css/clear-fix/ 
* `Flexbox` is more modern solution, but not yet supported on all browsers

## Aligning elements with same 'column' width

Default behaviour adds `padding` and `border` width to element width.

* box-sizing: border-box; changes this behaviour to make padding and border part of element width.
* Wrapping element: As margin still adds to the width, a wrapping element without any padding, margin and border is the standard solution to solve that
* Be aware when using `inline-block` that space use pixel too '...</div><div>...' != '...</div>  <div>...' 

## Position

Standard position is `static`. To position an child element with `absolut` position within it's parent the parent must have `relative` as position
