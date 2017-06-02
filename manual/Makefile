TARGET = manual

.SUFFIXES: .tex .pdf
.PHONY: clean clobber pdf

pdf: *.tex
	latexmk -pdf $(TARGET).tex

# Remove all intermediate files
clean:
	rm *.aux *.dvi *.fdb_latexmk *.fls *.log *.out *.toc

# Remove all intermediate and final compiled files
clobber: clean
	rm $(TARGET).pdf
