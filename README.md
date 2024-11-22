# AbstractAlgebraBook

### Lecture Notes on Abstract Algebra

This repository contains the source files for my book
*Lecture Notes on Abstract Algebra*.

A copy of the compiled PDF file can be downloaded from the author's
home page at <https://doty.math.luc.edu>.


The book is an open source, open textbook. The book's source code is
licensed under the MIT license and the content is licensed under a
Creative Commons BY license. In short, this means that you are free to
copy and modify the material for your own use as long as you provide
attribution. (You may want to read the actual licenses; see below.)


#### Dependencies

In order to make changes, you must use LaTeX; see
<https://www.latex-project.org>. You can install LaTeX on your local
machine, or alternatively use some online tool such as
[Overleaf](https://www.overleaf.com/) or
[CoCalc](https://cocalc.com/) to do the work in a browser.

#### Making changes

If you just want a copy of the PDF, see the second paragraph. If you
wish to make changes, then one way is to copy or clone the repository
and change your local copy using an editor.
In that case, assuming that you have a local copy of
LaTeX installed on your system, you can compile a new PDF that
incorporates your changes by running the following commands:
```
pdflatex all-in-one
pdflatex all-in-one
makeindex all-in-one
pdflatex all-in-one
pdflatex all-in-one
```
in a terminal. (This assumes that you have kept the name of the main
file `all-in-one.tex` intact. If you change that name, then use the
new name instead.)  Yes, you do need to run pdflatex more than
once, and makeindex at least once.
There are other approaches and other compilation commands
available; see the LaTeX documentation for your local installation
for details.


#### Licences

The book's content is published under a
[CC BY](https://creativecommons.org/licenses/by/4.0)
License, which means
that you can distribute, remix, adapt, and build upon the material for
any purpose, even commercially, as long as you give appropriate
credit, provide a link to the license, and indicate if changes were
made.

The source code is free software; you can redistribute it and/or
modify it under the terms of the
[MIT License](https://opensource.org/license/mit).
