all: thesis.pdf

thesis.pdf: thesis.tex sources.bib aalto-thesis.sty
	/usr/texbin/pdflatex thesis.tex > /dev/null
	/usr/texbin/bibtex thesis > /dev/null
	/usr/texbin/pdflatex thesis.tex > /dev/null
	/usr/texbin/pdflatex thesis.tex > /dev/null
