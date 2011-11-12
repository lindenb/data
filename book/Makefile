all:hacks.pdf tcltk.pdf bio.pdf

%.pdf:%.dvi
	dvipdf $<
%.dvi:%.tex
	latex $<
clean:
	rm -f *.dvi *.log *.aux *.out
