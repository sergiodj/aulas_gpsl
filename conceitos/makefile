.PHONY : all imagens

all: conceitos.pdf

%.pdf: %.tex imagens
	pdflatex --interaction=nonstopmode $<

imagens: imagens/linking.pdf imagens/compiler.pdf

%.pdf: %.dot
	dot -Tpdf $*.dot > $*.pdf
