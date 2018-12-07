UBSMC.pdf slides.pdf: UBSMC.aux UBSMC.tex slides.tex
	pdflatex UBSMC.tex
	bibtex UBSMC.aux
	pdflatex UBSMC.tex
	pdflatex slides.tex

.PHONY: clean

clean:
	rm -f *.log *.out
