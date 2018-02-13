FIRST := David
LAST := Tyler
MAJOR := CE

RESUME := resume.pdf

all:: $(RESUME)

%.pdf: %.tex
	pdflatex $<

install::
	mv $(RESUME) $(FIRST)$(LAST)_$(MAJOR).pdf
