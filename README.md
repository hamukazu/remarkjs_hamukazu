# remarkjs_hamukazu
My own template for Remark.js slides which can be effectively used with MathJax.

## Purpose
This is not inteded for a general purpose, but only for my own convenience.

The problem with the default setting of [Remark.js](remarkjs.com) is
that some of mathematical formulas are not rendered correctly with
MathJax. This is a template to overcome it.

## How to Use
Write your Markdown text in CONTENT.md and open `index.html`, or write in any file and open `index.html?<filename>`

Note: This has to be run with a HTTP server because it includes an outer file, while if your MD is written in `<textarea>` in the HTML file, it is OK just to open the file without a server.

A sample of CONTENT.md is included in this repository, and its demo is available [here](http://hamukazu.githup.io/remarkjs_hamukazu).

