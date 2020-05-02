# graphics2pdf
Experimental R code that converts (via LaTeX) a collection of graphic files into a single PDF file with one graphic per page

# Installation
First, download the tarball (i.e. the file named graphics2pdf_devel.tar.gz). Next, run:

    system("R CMD INSTALL --build graphics2pdf")

Alternatively, you can try installing the development version directly with the following code:

    install.packages(
      "https://github.com/gsucarrat/graphics2pdf/raw/master/graphics2pdf_devel.tar.gz",
      repos = NULL, type = "source"
    )

# Possible issues
The code has been developed and tested under Windows. It has not been tested on UNIX-like operating systems

# License
This package is free and open source software, licensed under GPL (>= 2)
