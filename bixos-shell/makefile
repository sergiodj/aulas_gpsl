.PHONY : all

all: bixos-shell.tex
	pdflatex --interaction=nonstopmode $<


%.pdf:
	dot -Tpdf $*.dot > $*.pdf
