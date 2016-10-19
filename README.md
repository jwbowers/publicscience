Contains files for slides and other materials a paper on the opportunities and
challenges of the recent move to into social and behavioral scientists in the
creation and evaluation of public policy.

To produce the slides on your local machine, you'll need R installed, and the package rmarkdown.

To install R, visit: https://cran.r-project.org/

To intall rmarkdown, open a session of R, and execute the following command in the console:

intall.packages("rmarkdown")

R will then install several dependencies (packages rmarkdown needs to run).

To produce the slides, open a terminal and navigate where you have saved the presentation files.

For example, if you've saved these in the documents folder:

cd ~/Documents/publicscience

If you wish to produce the slides for "Code as Communication", navigate to that subdirectory by typing:

cd presentations/

Then in the terminal run the following command:

Rscript -e "library(rmarkdown); render('publicscience.Rmd',output_format='all')"

To produce the beamer slides: publicscience.pdf




