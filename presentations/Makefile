SHELL = /bin/sh

publicscience.pdf: publicscience.Rmd sbst.beamer
	Rscript -e "library(rmarkdown); render('publicscience.Rmd',output_format='all')"

