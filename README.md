WebCleaner
==========

This is the source code for the Google Chrome Web Cleaner Extension.
This extension allows a user to filter specified content from the web.


The extension currently has two separate parts: a text filter and an image filter.
The code for both filters are contained in the filters.js file. The background.js file contains code
to hold the options and pass them to filters.js.
options.js contains code to handle the options.html page. Base64.js, Deflate.js, png.js, and Mutation_Summary are files
taken from other uses to facility the code found in filters.js.

Currently (10/27/13) The method used to handle the scanning of images for skin pixels could be possibly be improved.
Currently (10/27/13) There appears to be an issue where this extension seems to take up a large amount of memory,
particularly when the filters are applied to google searches, and especially on google image searches. This results
in the page loading much more slowly.
