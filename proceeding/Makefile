all: mazurov-chep2016.pdf

show: mazurov-chep2016.pdf
	open mazurov-chep2016.pdf&

mazurov-chep2016.pdf: mazurov-chep2016.tex figs/*.pdf
	pdflatex mazurov-chep2016.tex && pdflatex mazurov-chep2016.tex

clean:
	rm *.pdf *.aux *.log
