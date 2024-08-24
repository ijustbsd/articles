all:
	pdflatex main.tex
	# biber diplom
	pdflatex main.tex
	pdflatex main.tex
	# mv diplom.pdf Бабошин.pdf
	evince main.pdf &

clean:
	rm -f *.aux *.log *.out *.toc *.pdf *.bbl *.bcf *.blg *.xml *.nav *.snm
