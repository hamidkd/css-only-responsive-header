# CSS-Only Responsive Header

This is an ideal (in my opinion) CSS-Only Responsive Header.

- No JavaScript. So you can use it with whatever framework you use. (it uses a hidden checkbox instead of a button for hamburger menu)
- Works both in LTR and RTL documents
- link are immediate children of nav (instead of being wrapped in ul and li) which improves accessibility. (https://dockyard.com/blog/2019/11/29/using-nav-without-a-list-element)
- uses flexbox
- cool animations 

It is fork on MinzCode, css-only responsive header.

MinzCode CodePen: https://codepen.io/MinzCode/pen/bGexzXw
MinzCode Tutorial: https://www.youtube.com/watch?v=S-JyJCVx_4Y

## Things I changed form MinzCode:

- used flexbox instead of floats.
- replaced left and right attributes in the css with inset-inline-start and inset-inline-end to work both in LTR and RTL documents.
- changed html structure. Put logo outside of nav. (Maybe just a personal preference)
