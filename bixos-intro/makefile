.PHONY : all

all: bixos-softwarelivre.tex
	pdflatex --interaction=nonstopmode $<


%.pdf:
	dot -Tpdf $*.dot > $*.pdf
