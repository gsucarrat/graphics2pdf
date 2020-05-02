# graphics2pdf
Experimental R code that converts a collection of graphic files into a single PDF file with one graphic per page. The conversion is via LaTeX and takes place in two steps. First, a LaTeX file with the necessary code is created. Next, the PDF is created and opened. Optionally, the second step can be turned off by the user.

# Resource
* Video (1 minute): [Example of how to install and run graphics2pdf](https://github.com/gsucarrat/graphics2pdf/raw/master/how-to-install-and-run.mp4)

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
