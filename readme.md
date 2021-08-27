# CSS-Only Responsive Header

## Crdeit:

This is a fork on MinzCode, css-only responsive header.

MinzCode CodePen: https://codepen.io/MinzCode/pen/bGexzXw
MinzCode Tutorial: https://www.youtube.com/watch?v=S-JyJCVx_4Y

## Why it is ideal

- No JavaScript. So you can use it with whatever framework you use. (it uses a hidden checkbox instead of a button for hamburger menu)
- Works both in LTR and RTL documents
- link are immediate children of nav (instead of being wrapped in ```ul``` and ```li```) which improves accessibility. (https://dockyard.com/blog/2019/11/29/using-nav-without-a-list-element)
- uses flexbox
- cool animations 

## Screenshots

![Preview](preview.gif)

![Screenshot 2021-08-25 at 13-05-14 Document](https://user-images.githubusercontent.com/78935540/130834331-8e9849ff-469a-4b24-966d-82b1385917fa.png)![Screenshot 2021-08-25 at 13-05-06 Document](https://user-images.githubusercontent.com/78935540/130834335-fbb9f4c7-cdf3-4532-9d30-df6b75b7272d.png) ![Screenshot 2021-08-25 at 13-04-55 Document](https://user-images.githubusercontent.com/78935540/130834336-b94a1a9a-c654-473d-9cf8-852194c25fbe.png)






## Things I changed form MinzCode:

- used flexbox instead of floats.
- replaced left and right attributes in the css with inset-inline-start and inset-inline-end to work both in LTR and RTL documents.
- changed html structure. Put logo outside of nav. (Maybe just a personal preference)
- changed absolute positioning of header to sticky. (It sticks at the top of your site while you can use famous ```display: grid; grid-template-rows: auto 1fr auto;``` for layouting header, main and footer in body styles)
- used ```::before``` and ```::after``` to create hamburger menu instead of ```div```s. This makes html more semantic. I prefer two bars. but if you want three bars you can achieve it with styleing the labe itself. You need to adjust position of bars. don't forget to hide the middle bar when menu is open (checkbox is checked). 
- simplified the code a little bit
