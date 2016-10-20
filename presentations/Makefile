SHELL = /bin/sh

publicscience.pdf: publicscience.Rmd sbst.beamer
	Rscript -e "library(rmarkdown); render('publicscience.Rmd',clean=FALSE)"

publicscience_wmn.pdf: publicscience.pdf
	tail -n +2 publicscience.tex > publicscienceGood.tex && xelatexmk.sh publicscience_wmn.tex
