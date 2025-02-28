.DEFAULT_GOALS := zjuthesis

.PHONY: zjuthesis
zjuthesis:
	latexmk
	
all:
	latexmk -xelatex -outdir=./ zjuthesis
	rm -rf *.aux *.bbl *.bcf *.blg *.fdb_latexmk *.fls *.log *.xml *.toc *.xdv *.synctex.gz
	
clean:
	rm -rf *.aux *.bbl *.bcf *.blg *.fdb_latexmk *.fls *.log *.xml *.toc *.xdv *.synctex.gz