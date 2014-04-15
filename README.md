Booky-CSS
=========

A css framework for paged media. Created as an experiment :)

## Usage

You should create HTML page with proper markup, link CSS styles and optionally add Hyphenator.js (important when you use columns)

Next step is to „render” your document.
Simplest way to do it, is to print page to pdf in Opera (which have the best support of paged-media CSS, but still sucks at this - e.g. no page numbering.)

The better way to render it is to use Prince. You can download it from [http://www.princexml.com/download/](http://www.princexml.com/download/). After instalation you can comile book to pdf with simple command:

    prince book.html -o book.pdf

## TODO
1. Configuration options.
2. Create some script to generate booklets.
3. Better spacing between paragraphs.
4. Better internationalization.
5. …

## Contribution
Just fork this repository, create changes on **another** branch and push them, create pull request.
