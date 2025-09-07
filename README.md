# Nagatoisme
A barebones and simplifyed framework for putting personal papers online.

# How to add a new book
Firstly copy the book as a pdf file format, into the books directory.
Then in the index.html copy this line of code into the inclosed row class div element group.
Also change the name of "yourpdf" to the filename of the book.
```
<!-- This is the start of a book element -->
<div class="book">
    <embed src="books/yourpdf.pdf" width="400px" height="600px" />
    <a href="books/yourpdf.pdf" target="_blank"
        >Open in Fullscreen</a
    >
</div>
<!-- This is the end of a book element -->
```
