all:
	pdflatex main.tex

run:
	okular main.pdf & disown

bib:
	bibtex main

clean:
	rm -f  *.{hst,ver,toc,log,aux,out,dvi,bbl,blg,bcf,xml}
	mv main.pdf `basename ${PWD}`.pdf
	rm -f main.pdf

