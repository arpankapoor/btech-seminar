logs = *.aux *.bbl *.bcf *.blg *.lof *.log *.out *.run.xml *.toc

all: abstract.tex
	pdflatex $^
	biber abstract
	pdflatex $^
	pdflatex $^
	mv abstract.pdf arpan_b120555cs.pdf

clean:
	$(RM) $(logs)
