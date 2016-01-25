TARGETS = main

all: compile

compile:
	pdflatex --enable-write18 $(TARGETS) &&	pdflatex $(TARGETS) && pdflatex $(TARGETS)

clean:
	  rm -f *.aux *.bbl *.blg *.log $(TARGETS)
