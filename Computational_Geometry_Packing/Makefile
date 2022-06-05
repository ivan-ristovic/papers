paper.pdf: paper.aux paper.tex
	bibtex paper.aux
	pdflatex paper.tex
	pdflatex paper.tex
	
paper.aux: paper.tex
	pdflatex paper.tex

.PHONY: clean

clean:
	rm -f *.log *.out
