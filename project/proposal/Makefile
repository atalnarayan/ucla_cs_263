TEX    = proposal
PDF    = $(TEX).pdf
LATEX  = /usr/local/texlive/2025/bin/universal-darwin/pdflatex

.PHONY: all clean

all: $(PDF)

$(PDF): $(TEX).tex
	$(LATEX) -interaction=nonstopmode $(TEX).tex
	$(LATEX) -interaction=nonstopmode $(TEX).tex

clean:
	rm -f $(TEX).aux $(TEX).log $(TEX).out $(TEX).toc $(TEX).bbl $(TEX).blg
