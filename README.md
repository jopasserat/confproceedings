A very basic template to build proceedings from a set of PDF camera-ready papers.

## Usage ##

  1- Copy all the papers in a `papers` folder
  2- Update the list in *Proceedings.tex*
  3- Update the front page and foreword respectively in *header.tex* and *editorial.tex*
  4- Move the style and class files from libs if you cannot find them on your system
  5- Compile: `pdflatex -output-dir=build -shell-escape -synctex=1  Proceedings.tex`
  6- Admire


## Required packages ##
  - confproc.cls
  - newapave.sty

(available as part of the `texlive-publishers` distribution on Debian and in the `lib` folder)

