.PHONY: clean

%.pdf: %.tex $(DEPENDS)
		rubber  --module xelatex -f --pdf -s $<
		rubber-info --check $<

clean:
		rm -rf *.aux *.bbl *.blg *.log *.pdf *.toc *.snm *.out *.nav tags
