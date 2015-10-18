logs=*.aux *.bbl *.bcf *.blg *.lof *.log *.nav *.out *.run.xml *.snm *.toc

all: main.tex
	xelatex $^
	bibtex main.aux
	xelatex $^
	xelatex $^

clean:
	$(RM) $(logs)

.PHONY: all clean
