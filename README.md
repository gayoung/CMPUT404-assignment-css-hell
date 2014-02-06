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

Assignment Part I:
==================

The changes made to the project gutenberg HTML files are listed below:
- added class called copyright to pre element in the beginning.
- had to change the href on surrounding anchor element to each images to
properly link the file to gutenberg images and also do the same for the 
img src attribute values.
- Wrapped all the paragraph elements associated with each images or in
 between two header elements into a div with class name storyContainer.
- deleted a div with 3 breaks in document1.html and in document3.html(the br element spacing was replaced with css margins)
- added a class sidenote to a para that had a small note below part I title in document3.html

Assignment Part II:
===================
- resume.png and work.png was obtained from:
http://openclipart.org/detail/155095/resume-by-mazeo