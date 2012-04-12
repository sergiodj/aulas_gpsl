.PHONY : all imagens

all: conceitos.tex imagens
	pdflatex --interaction=nonstopmode $<

imagens: imagens/compilation_process.dot
	dot -Tpng $< > imagens/compilation_process.png
