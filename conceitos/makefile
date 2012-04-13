.PHONY : all imagens

all: conceitos.tex imagens
	pdflatex --interaction=nonstopmode $<

imagens: imagens/linking.pdf imagens/compiler.pdf

%.pdf:
	dot -Tpdf $*.dot > $*.pdf
