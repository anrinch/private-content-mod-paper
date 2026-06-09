TARGET=main

all: pdf

pdf:
	latexmk -pdf $(TARGET).tex

clean:
	latexmk -c

cleanall: clean
	latexmk -c
	rm -f $(TARGET).bbl
	rm -f $(TARGET).pdf
	rm -f *.gz
