# pdfjet-data

The example data of [PDFjet](https://github.com/edragoev1/pdfjet): the text,
CSV, XML, Markdown, image and PDF files its examples and tests read.

This repository is the `data` directory of
[edragoev1/pdfjet](https://github.com/edragoev1/pdfjet), where it is a git
submodule. Clone PDFjet with `git clone --recurse-submodules`, or run
`git submodule update --init` in a clone, to get it there.

## Where the data comes from

- `the-idiot.txt` is "The Idiot" by Fyodor Dostoyevsky, in the English
  translation by Eva Martin (1915), from Project Gutenberg, eBook #2638, and
  in the public domain. `the-idiot-source.txt` says where it comes from and
  how the text was prepared. `dostoevsky.txt` is from the same translation.
- `languages` holds sample text in the languages and scripts PDFjet draws.
- `testPDFs/PDFjetLogo.pdf`, `markdown` and `invoice` are PDFjet's own
  (`invoice/logo.svg` is the logo of a fictional print shop);
  `testPDFs/scanned-linearized.pdf` is written by `util/make-scanned-pdf.py`
  of PDFjet.
- The other files are sample data for the examples: the tables they draw, an
  invoice in the Factur-X format, and a form they read pages from.
