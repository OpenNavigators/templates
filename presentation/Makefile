PROJNAME=VinsFromScratch

.PHONY: $(PROJNAME).pdf all clean

all: $(PROJNAME).pdf

$(PROJNAME).pdf: main.tex
	latexmk -pdf -pdflatex="pdflatex -interactive=nonstopmode" -use-make $<

cleanall:
	latexmk -C

clean:
	latexmk -c
