# graphics2pdf
Experimental R code that converts a collection of graphic files into a single PDF file via LaTeX

# Installation
To install the version available here at Github, first download the tarball (i.e. the file named graphics2pdf_devel.tar.gz). Next, run:

    system("R CMD INSTALL --build graphics2pdf")

Alternatively, you can try installing the development version directly from GitHub with the following code:

    install.packages(
      "https://github.com/gsucarrat/graphics2pdf/raw/master/graphics2pdf_devel.tar.gz",
      repos = NULL, type = "source"
    )

# License
This package is free and open source software, licensed under GPL (>= 2)
