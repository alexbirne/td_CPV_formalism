all:
	lualatex HFLAV.tex
	biber HFLAV
	lualatex HFLAV.tex
	lualatex HFLAV.tex
	rm -f *.log *.bak *.aux *.bbl *.blg *.idx *.toc *.out *~ *.synctex.gz *.run.xml *.bcf

clean:
	rm -f *.log *.bak *.aux *.bbl *.blg *.idx *.toc *.out *~ *.synctex.gz *.run.xml *.bcf

clean-all:
	rm -f *.dvi *.log *.bak *.aux *.bbl *.blg *.idx *.ps *.eps *.pdf *.toc *.out *~ *.synctex.gz *.run.xml *.bcf

