# CV template - PDF from rmarkdown
This is a more generic version of my own CV (available at https://www.olssoncollentine.com/files/cv.pdf) which can be used as a template. It is adapted from Steven Miller's template: http://svmiller.com/blog/2016/03/svm-r-markdown-cv/

The main difference from Steven Miller's version is that I:

1) Do all my formatting via R-code instead of manually 
2) Use slightly different formatting

That is, I use `knitr` tables together with the R-package `kableExtra` to format my output rather than writing manual markdown and latex for each data point in the R-markdown file. This has the advantage that data input is kept separate from formatting, and is as simple as possible.

The rmarkdown -> PDF translation is guided by a latex template (svm-latex-cv.tex) that I copied from Steven Miller and made some minor changes to. I suspect there is a lot of superfluous code in this template, but since I only have very basic latex skills I leave to someone more expert to clean it up. Make sure if using this rmarkdown template that latex packages are installed automatically.

For the filler data in this template I mainly copied from Steven Miller's  William Sealy Gosset CV, but some datapoints are just made up. Below a picture of the template output.


![picture](https://github.com/Jaeoc/CV-template-rmarkdown/raw/master/cv_template.png)
