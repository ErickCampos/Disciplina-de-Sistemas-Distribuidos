target=sbc-template

all:
	pdflatex $(target).tex
	bibtex $(target).aux
	pdflatex $(target).tex
	pdflatex $(target).tex
	make clean

clean:
	rm -f *.aux *.bbl *.blg *.dvi *.log *.out *.upa *.upb
