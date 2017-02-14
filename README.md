Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


modifications
=============

Added one line of code at the end of head part in each html file. The specific changed shown below,

```html
<link href="style.css" rel="stylesheet" type="text/css">
```

This line will import my custom CSS. Since it's at the end of head tag, it will overwrite the default style in html.

The specific component that have been overwrite is the paragraph, headers, image, hr tag, and body's background.  Details of changes on each component have been listed bellow,

- **P (paragraph)**
    The text indent changes to 2em. Padding left and right have been set to 10em. The font-family is now cursive and font size been changed to 15pt.
    
- **body**
    Applied an background image by url.
    
- **hr**
    Reset height to 0px. Set background color and border color to black. Applied border radius as 10px. Set border width to 2px, and set opacity to 0.5.

- **H1,H2,H3,H4,H5,H6 (headers)**
    Changed font family to fantasy.

- **img (image)**
    Applied sepia filter and set opacity to 0.7.
