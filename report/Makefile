all: report.latex
	pdflatex -shell-escape report.latex ; pdflatex -shell-escape report.latex

pres: presentation.latex
	pdflatex -shell-escape presentation.latex ; pdflatex -shell-escape presentation.latex

clean:
	rm -f report.log report.aux report.toc presentation.log presentation.aux *.nav *.out *.snm *.vrb