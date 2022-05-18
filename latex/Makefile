.PHONY: clean

all: resume.pdf

%.pdf: %.tex $(DEPENDS)
		@echo '.........: pdflatex running pass 1...'
		pdflatex $< -o $@ 2>&1 | tee errors.err

clean:
		rm -rf *.aux *.bbl *.blg *.log *.pdf *.toc *.snm *.out *.nav tags
