g-barcode
=========
A barcode library for PGF/TikZ TeX package.

How it works
============
The g-barcode TeX package produces the \pgfbarcode{<code>} macro to insert into
a LaTeX source file. After the compilation with pdflatex, you achieve the pdf file.
At the moment only the code39 1D format is supported.

In the TeX world exist the powerfull pst-barcode package, as part of pstricks
graphic bundle. With it you achieve a Postscript file that can be convert into pdf format.

Code example
============
To draw the barcode corresponding to the text ´0123456789´ you must insert
the macro in a ´tikzpicture´ or in a ´pgfpicture´ LaTeX environment:
````
\begin{tikzpicture}
\pgfbarcode{0123456789}
\end{tikzpicture}
````
In the LaTeX document preamble, is necessary to load almost the PGF package and
the g-barcode package.

Future development
==================
The command syntax can change in the future to ensure a better intergration
with PGF package.

The g-barcode aims to became a multi-format package with TeX/LaTeX/ConTeXt
frontend, to produce smartly different kind of barcodes.

