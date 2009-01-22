f1=quiz
f2=recitation

all: $(f1).pdf $(f2).pdf

$(f1).pdf: $(f1).tex
	pdflatex $(f1).tex

$(f2).pdf: $(f2).tex
	pdflatex $(f2).tex

clean:
	rm -f $(f1).aux $(f1).log $(f2).aux $(f2).log
